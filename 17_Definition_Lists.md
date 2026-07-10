# Definition Lists in Markdown

A **definition list** is used to display a term followed by its definition. It is useful for creating glossaries, dictionaries, or explaining technical terms.

> **Note:** Definition lists are **not supported by standard Markdown or GitHub Flavored Markdown (GFM)**. They are supported by some Markdown processors such as **Pandoc** and **PHP Markdown Extra**.

---

## Syntax

Write the term on one line, followed by a colon (`:`) and its definition on the next line.

### Markdown

```md
Python
: A high-level programming language.

Markdown
: A lightweight markup language.
```

### Output

Python
: A high-level programming language.

Markdown
: A lightweight markup language.

---

## Multiple Definitions

A term can have more than one definition.

### Markdown

```md
Python
: A programming language.
: A popular language for data science and web development.
```

### Output

Python
: A programming language.
: A popular language for data science and web development.

---

## Best Practices

- Use definition lists for glossaries and technical documentation.
- Keep definitions short and clear.
- Check whether your Markdown editor supports definition lists before using them.

---

## Summary

Definition lists help organize terms and their meanings in a clean format.

| Feature | Syntax |
|---------|--------|
| Definition List | `Term`<br>`: Definition` |
| Multiple Definitions | `Term`<br>`: Definition 1`<br>`: Definition 2` |