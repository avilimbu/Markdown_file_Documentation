# Mathematical Expressions in Markdown

Mathematical expressions allow you to write equations and formulas using **LaTeX syntax**. They are commonly used in scientific, engineering, and educational documents.

> **Note:** Mathematical expressions are **not supported by standard Markdown**. They are supported by platforms such as **GitHub (with MathJax support)**, **Jupyter Notebook**, **Obsidian**, and many Markdown editors.

---

## Inline Math

Use a single dollar sign (`$`) before and after the equation.

### Syntax

```md
$E = mc^2$
```

### Output

$E = mc^2$

---

## Block Math

Use double dollar signs (`$$`) to display an equation on its own line.

### Syntax

```md
$$
E = mc^2
$$
```

### Output

$$
E = mc^2
$$

---

## Example

### Markdown

```md
The quadratic formula is:

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
```

### Output

The quadratic formula is:

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

---

## Common LaTeX Symbols

| Symbol | LaTeX |
|--------|--------|
| Fraction | `\frac{a}{b}` |
| Square Root | `\sqrt{x}` |
| Superscript | `x^2` |
| Subscript | `x_1` |
| Greek Letter | `\alpha`, `\beta`, `\pi` |
| Summation | `\sum` |
| Integral | `\int` |

---

## Best Practices

- Use **inline math** for short equations.
- Use **block math** for large or complex formulas.
- Verify that your Markdown editor supports LaTeX before using mathematical expressions.

---

## Summary

Markdown supports mathematical expressions using **LaTeX syntax** on supported platforms.

| Type | Syntax |
|------|--------|
| Inline Math | `$...$` |
| Block Math | `$$...$$` |