# Keyboard Keys in Markdown

Keyboard keys are used to display keyboard shortcuts clearly in documentation and tutorials. This is commonly done using the HTML `<kbd>` tag.

> **Note:** The `<kbd>` tag is an HTML element supported by GitHub and many Markdown editors.

---

## Single Key

Use the `<kbd>` tag to display a single keyboard key.

### Syntax

```html
<kbd>Enter</kbd>
```

### Output

<kbd>Enter</kbd>

---

## Keyboard Shortcut

Combine multiple `<kbd>` tags with a plus sign (`+`).

### Markdown

```html
<kbd>Ctrl</kbd> + <kbd>C</kbd>
```

### Output

<kbd>Ctrl</kbd> + <kbd>C</kbd>

---

## Example

### Markdown

```html
To save a file, press <kbd>Ctrl</kbd> + <kbd>S</kbd>.

To paste, press <kbd>Ctrl</kbd> + <kbd>V</kbd>.
```

### Output

To save a file, press <kbd>Ctrl</kbd> + <kbd>S</kbd>.

To paste, press <kbd>Ctrl</kbd> + <kbd>V</kbd>.

---

## Common Keyboard Shortcuts

| Action | Markdown |
|--------|----------|
| Copy | `<kbd>Ctrl</kbd> + <kbd>C</kbd>` |
| Paste | `<kbd>Ctrl</kbd> + <kbd>V</kbd>` |
| Cut | `<kbd>Ctrl</kbd> + <kbd>X</kbd>` |
| Save | `<kbd>Ctrl</kbd> + <kbd>S</kbd>` |
| Undo | `<kbd>Ctrl</kbd> + <kbd>Z</kbd>` |
| Redo | `<kbd>Ctrl</kbd> + <kbd>Y</kbd>` |

---

## Best Practices

- Use `<kbd>` to display keyboard keys and shortcuts.
- Write each key inside its own `<kbd>` tag.
- Use a plus sign (`+`) between keys in a shortcut.

---

## Summary

The `<kbd>` tag makes keyboard shortcuts easy to read in Markdown documentation.

| Feature | Syntax |
|---------|--------|
| Single Key | `<kbd>Enter</kbd>` |
| Keyboard Shortcut | `<kbd>Ctrl</kbd> + <kbd>C</kbd>` |