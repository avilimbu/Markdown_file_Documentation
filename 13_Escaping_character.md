# Escaping Characters in Markdown

Some characters in Markdown have special meanings. To display them as plain text, use a **backslash (`\`)** before the character. This is called **escaping**.

---

## Syntax

```md
\special-character
```

---

## Common Escaped Characters

| Character | Escape Syntax | Output |
|-----------|---------------|--------|
| `*` | `\*` | \* |
| `_` | `\_` | \_ |
| `` ` `` | `` \` `` | \` |
| `#` | `\#` | \# |
| `[` | `\[` | \[ |
| `]` | `\]` | \] |
| `(` | `\(` | \( |
| `)` | `\)` | \) |
| `!` | `\!` | \! |
| `|` | `\|` | \| |
| `>` | `\>` | \> |
| `-` | `\-` | \- |

---

## Example

### Markdown

```md
\# This is not a heading

\* This is not a list item

Use the \`print()\` function.
```

### Output

\# This is not a heading

\* This is not a list item

Use the \`print()\` function.

---

## When to Use Escaping

Use escaping when you want Markdown symbols to appear as plain text instead of being interpreted as formatting.

For example:

Instead of creating a heading:

```md
# Heading
```

Display the symbol itself:

```md
\# Heading
```

---

## Best Practices

- Use escaping only when necessary.
- Remember that **backslash (`\`)** is the escape character in Markdown.
- If you're writing Markdown tutorials or documentation, escaping is very useful for showing syntax.

---

## Summary

Escaping allows you to display Markdown symbols as plain text by placing a backslash (`\`) before them.

| Purpose | Example |
|---------|---------|
| Show `#` | `\# Heading` |
| Show `*` | `\* Text` |
| Show `` ` `` | `` \`code\` `` |
| Show `[` | `\[` |