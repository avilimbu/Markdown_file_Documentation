# HTML in Markdown

Markdown supports HTML, allowing you to use HTML tags when Markdown syntax is not enough.

---

## Why Use HTML?

HTML can be used to:

- Resize images
- Change text color
- Add line breaks
- Create collapsible sections
- Align content
- Add custom formatting

---

## Line Break

Use the `<br>` tag to move text to a new line.

### Markdown

```html
Hello<br>
World
```

### Output

Hello<br>
World

---

## Image with Size

Markdown cannot resize images directly, but HTML can.

### Markdown

```html
<img src="images/python.png" alt="Python Logo" width="200">
```

---

## Center Align Text

Use the `<div>` tag with the `align` attribute.

### Markdown

```html
<div align="center">
This text is centered.
</div>
```

---

## Text Formatting

HTML tags can also format text.

### Markdown

```html
<b>Bold</b>

<i>Italic</i>

<u>Underline</u>
```

### Output

<b>Bold</b>

<i>Italic</i>

<u>Underline</u>

---

## Collapsible Section

Use the `<details>` and `<summary>` tags to hide content.

### Markdown

```html
<details>
<summary>Click to Expand</summary>

This content is hidden until you click the title.

</details>
```

### Output

<details>
<summary>Click to Expand</summary>

This content is hidden until you click the title.

</details>

---

## Best Practices

- Use Markdown whenever possible.
- Use HTML only when Markdown doesn't support the feature you need.
- Remember that some Markdown editors may not support every HTML tag.

---

## Summary

HTML extends Markdown by providing additional formatting options.

| Feature | HTML Tag |
|---------|----------|
| Line Break | `<br>` |
| Image | `<img>` |
| Bold | `<b>` |
| Italic | `<i>` |
| Underline | `<u>` |
| Center Align | `<div align="center">` |
| Collapsible Section | `<details>` |