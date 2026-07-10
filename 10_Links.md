# Links in Markdown

Links are used to connect your document to web pages, files, email addresses, or different sections of the same document.

---

## Inline Links

An inline link consists of **link text** and a **URL**.

### Syntax

```md
[Link Text](URL)
```

### Markdown

```md
[OpenAI](https://openai.com)
```

### Output

[OpenAI](https://openai.com)

---

## Links with a Title

You can add a title that appears when you hover over the link.

### Syntax

```md
[Link Text](URL "Title")
```

### Markdown

```md
[OpenAI](https://openai.com "Visit OpenAI")
```

---

## Automatic Links

Wrap a URL or email address inside angle brackets (`< >`).

### Markdown

```md
<https://github.com>

<example@gmail.com>
```

### Output

<https://github.com>

<example@gmail.com>

---

## Reference Links

Reference links keep your Markdown cleaner by defining the URL separately.

### Markdown

```md
Visit the [Python Website][python].

[python]: https://www.python.org
```

### Output

Visit the [Python Website][python].

[python]: https://www.python.org

---

## Internal Links

You can create links to headings within the same document.

### Markdown

```md
## Installation

[Go to Installation](#installation)
```

### Output

If a heading named **Installation** exists, clicking the link will jump to that section.

---

## Best Practices

- Use meaningful link text instead of generic words like "Click Here."
- Use reference links when the same URL is used multiple times.
- Check that all links work correctly before publishing.

---

## Summary

Markdown supports different types of links for different purposes.

| Link Type | Syntax |
|-----------|--------|
| Inline Link | `[Text](URL)` |
| Link with Title | `[Text](URL "Title")` |
| Automatic Link | `<https://example.com>` |
| Email Link | `<example@email.com>` |
| Reference Link | `[Text][id]` |
| Internal Link | `[Text](#heading-name)` |