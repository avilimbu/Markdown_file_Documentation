# Images in Markdown

Images are used to make your documents more attractive and easier to understand. Markdown allows you to add images using a simple syntax.

---

## Basic Image

The syntax for adding an image is similar to a link, but with an exclamation mark (`!`) at the beginning.

### Syntax

```md
![Alt Text](image-path)
```

### Markdown

```md
![Python Logo](images/python.png)
```

### Output

Displays the image located at `images/python.png`.

> **Note:** **Alt Text** is displayed if the image cannot be loaded and also improves accessibility.

---

## Image from a URL

You can also display an image from the internet.

### Markdown

```md
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

### Output

Displays the image from the given URL.

---

## Clickable Image

You can make an image clickable by placing the image syntax inside a link.

### Markdown

```md
[![Python Logo](images/python.png)](https://www.python.org)
```

### Output

Clicking the image opens the Python website.

---

## Image with HTML

Markdown does not support resizing images directly. You can use HTML for more control.

### Markdown

```html
<img src="images/python.png" alt="Python Logo" width="200">
```

### Output

Displays the image with a width of **200 pixels**.

---

## Image Paths

There are two common ways to specify an image path.

### Relative Path

Used when the image is inside your project.

```md
![Logo](images/logo.png)
```

### Absolute URL

Used when the image is hosted online.

```md
![Logo](https://example.com/logo.png)
```

---

## Best Practices

- Always provide meaningful **Alt Text**.
- Store project images in a separate folder (such as `images/` or `assets/`).
- Use relative paths for project images.
- Resize large images using HTML when needed.

---

## Summary

Markdown makes it easy to add images to your documents.

| Image Type | Syntax |
|------------|--------|
| Basic Image | `![Alt Text](image.png)` |
| Image from URL | `![Alt Text](https://example.com/image.png)` |
| Clickable Image | `[![Alt Text](image.png)](URL)` |
| Resized Image (HTML) | `<img src="image.png" width="200">` |