# Footnotes in Markdown

Footnotes allow you to add additional information or references without interrupting the main content. They are supported in **GitHub Flavored Markdown (GFM)** and many modern Markdown editors.

---

## Syntax

A footnote consists of:

1. A **reference** in the text.
2. A **footnote definition** at the end of the document.

### Markdown

```md
Markdown is easy to learn.[^1]

[^1]: Markdown is a lightweight markup language.
```

### Output

Markdown is easy to learn.[^1]

[^1]: Markdown is a lightweight markup language.

---

## Multiple Footnotes

You can add more than one footnote.

### Markdown

```md
Python is beginner-friendly.[^1]

Markdown is widely used for documentation.[^2]

[^1]: Python has simple syntax.
[^2]: Markdown is supported by GitHub.
```

---

## Best Practices

- Keep footnotes short and relevant.
- Place footnote definitions at the end of the document.
- Use clear numbering or descriptive labels.

---

## Summary

Footnotes are useful for adding references, explanations, or extra information without cluttering the main content.

| Feature | Syntax |
|---------|--------|
| Footnote Reference | `[^1]` |
| Footnote Definition | `[^1]: Your footnote text` |