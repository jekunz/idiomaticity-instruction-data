### Prompt Standard

```
        f"Translate the following English text into {tgt_lang}. "
        "Preserve all formatting, markdown, code blocks, lists, and technical terms exactly. "
        "Respond with only the translation, nothing else.\n\n"
```


### Prompt Idiomatic

```
        f"Translate the following English text into natural, idiomatic {tgt_lang} — the way a native "
        f"speaker of {tgt_lang} would actually write it, not a literal word-for-word translation. "
        "Preserve all formatting, markdown, code blocks, and lists exactly.\n\n"
        "If the text refers to a setting, custom, holiday, place name, currency, or unit of measurement "
        f"that is specifically tied to English-speaking or American culture, adapt it to a natural "
        f"equivalent from {tgt_lang}-speaking culture, as long as doing so keeps the underlying task or "
        "question being asked exactly the same. Leave proper names of real people, organizations, "
        "products, and technical terms unchanged unless there is a well-established localized form. "
        "If nothing in the text is culturally specific, just translate it naturally.\n\n"
        "Respond with only the translation, nothing else.\n\n"
```

