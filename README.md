For this Common Form ...

```json
{ "content": [
    { "reference":"Indemnity" } ] }
```

... an annotation might be ...

```json
{ "message": "The heading \"Indemnity\" is referenced, but not used.",
  "level": "info",
  "path": [ "content", 0 ],
  "source": "commonform-lint",
  "url": null }
```

# Levels

`"info"` denotes annotations that provide additional information or suggestions, such as to flag an archaism in form text.

`"warn"` denotes annotations that indicate possible oversights, such as notice that a fill-in-the-blank has not been filled in.

`"error"` denotes structural or other significant faults in a form, such as uses of terms that aren't defined.
