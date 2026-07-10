# Tables in Markdown

Tables are used to organize data into rows and columns, making information easier to read and compare.

---

## Basic Table

A table is created using the pipe (`|`) symbol and hyphens (`-`).

### Syntax

```md
| Header 1 | Header 2 |
|----------|----------|
| Data 1   | Data 2   |
| Data 3   | Data 4   |
```

### Output

| Header 1 | Header 2 |
|----------|----------|
| Data 1   | Data 2   |
| Data 3   | Data 4   |

---

## Column Alignment

You can align the content of a column using colons (`:`).

| Alignment | Syntax |
|-----------|--------|
| Left | `:-----` |
| Center | `:----:` |
| Right | `-----:` |

### Markdown

```md
| Name | Age | Marks |
|:-----|:---:|------:|
| Ram  | 20  | 95 |
| Hari | 21  | 90 |
```

### Output

| Name | Age | Marks |
|:-----|:---:|------:|
| Ram  | 20  | 95 |
| Hari | 21  | 90 |

---

## Table with Formatting

Markdown formatting such as **bold**, *italic*, and `inline code` can be used inside table cells.

### Markdown

```md
| Name | Language |
|------|----------|
| **John** | `Python` |
| *Jane* | `Java` |
```

### Output

| Name | Language |
|------|----------|
| **John** | `Python` |
| *Jane* | `Java` |

---

## Best Practices

- Keep the number of columns consistent.
- Use meaningful column headings.
- Align columns when it improves readability.
- Use tables only for structured data.

---

## Summary

Tables are useful for displaying structured information in a clean and organized way.

| Feature | Syntax |
|---------|--------|
| Table | `| Column | Column |` |
| Header Separator | `|-----|-----|` |
| Left Align | `:-----` |
| Center Align | `:----:` |
| Right Align | `-----:` |