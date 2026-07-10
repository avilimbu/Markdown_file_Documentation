# Superscript and Subscript in Markdown

Superscript and subscript are used to display text slightly above or below the normal text line. Since standard Markdown doesn't support them directly, HTML tags are commonly used.

> **Note:** The `<sup>` and `<sub>` tags are HTML elements supported by GitHub and many Markdown editors.

---

## Superscript

Superscript displays text above the normal line.

### Syntax

```html
x<sup>2</sup>
```

### Output

x<sup>2</sup>

---

## Subscript

Subscript displays text below the normal line.

### Syntax

```html
H<sub>2</sub>O
```

### Output

H<sub>2</sub>O

---

## Example

### Markdown

```html
E = mc<sup>2</sup>

The chemical formula for water is H<sub>2</sub>O.

The chemical formula for carbon dioxide is CO<sub>2</sub>.
```

### Output

E = mc<sup>2</sup>

The chemical formula for water is H<sub>2</sub>O.

The chemical formula for carbon dioxide is CO<sub>2</sub>.

---

## Best Practices

- Use `<sup>` for exponents, powers, and ordinal numbers (e.g., 1<sup>st</sup>).
- Use `<sub>` for chemical formulas, mathematical variables, and scientific notation.
- Use HTML tags since standard Markdown does not support superscript and subscript.

---

## Summary

Superscript and subscript can be added to Markdown using HTML tags.

| Feature | Syntax | Example |
|---------|--------|---------|
| Superscript | `<sup>` | `x<sup>2</sup>` |
| Subscript | `<sub>` | `H<sub>2</sub>O` |