# Headings in Markdown

> Learn how to organize your Markdown documents using headings and subheadings.

---

# Table of Contents

- [What are Headings?](#what-are-headings)
- [Why Use Headings?](#why-use-headings)
- [Heading Levels](#heading-levels)
- [Syntax](#syntax)
- [Examples](#examples)
- [Best Practices](#best-practices)
- [Common Mistakes](#common-mistakes)
- [When to Use Each Heading Level](#when-to-use-each-heading-level)
- [Real-World Example](#real-world-example)
- [Summary](#summary)

---

# What are Headings?

Headings are titles and subtitles that organize the content of a Markdown document into sections. They create a clear hierarchy, making your document easier to read and navigate.

Think of headings like the chapters and subchapters in a book.

For example:

```
Book
│
├── Chapter 1
│   ├── Topic 1
│   ├── Topic 2
│
├── Chapter 2
│   ├── Topic 1
│   ├── Topic 2
```

Markdown headings work in exactly the same way.

---

# Why Use Headings?

Headings provide several benefits:

- Organize content into logical sections.
- Improve readability.
- Make long documents easier to navigate.
- Help generate automatic Table of Contents (TOC).
- Improve accessibility.
- Improve SEO when Markdown is converted to HTML.
- Help GitHub create section links automatically.

Without headings, a document becomes difficult to read.

---

# Heading Levels

Markdown provides **six heading levels**.

| Level | Symbol | HTML Equivalent |
|--------|--------|-----------------|
| Heading 1 | `#` | `<h1>` |
| Heading 2 | `##` | `<h2>` |
| Heading 3 | `###` | `<h3>` |
| Heading 4 | `####` | `<h4>` |
| Heading 5 | `#####` | `<h5>` |
| Heading 6 | `######` | `<h6>` |

Each additional `#` represents a lower-level heading.

---

# Syntax

General syntax:

```md
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

Notice that there is a **space after the `#` symbols**. This is the recommended syntax.

---

# Examples

## Heading 1

Markdown

```md
# My Portfolio
```

Output

# My Portfolio

---

## Heading 2

Markdown

```md
## About Me
```

Output

## About Me

---

## Heading 3

Markdown

```md
### Education
```

Output

### Education

---

## Heading 4

Markdown

```md
#### Skills
```

Output

#### Skills

---

## Heading 5

Markdown

```md
##### Programming Languages
```

Output

##### Programming Languages

---

## Heading 6

Markdown

```md
###### Python
```

Output

###### Python

---

# Heading Hierarchy

A good Markdown document follows a logical hierarchy.

Example:

```md
# Python Programming

## Introduction

### Variables

### Data Types

## Functions

### Parameters

### Return Values

## Object-Oriented Programming

### Classes

### Objects
```

Hierarchy

```
Python Programming
│
├── Introduction
│   ├── Variables
│   └── Data Types
│
├── Functions
│   ├── Parameters
│   └── Return Values
│
└── Object-Oriented Programming
    ├── Classes
    └── Objects
```

---

# Best Practices

## 1. Use only one H1 (`#`) per document

Usually, the main title of the document should be the only H1.

Example

```md
# Python Notes
```

---

## 2. Follow the correct hierarchy

Correct

```md
# Python

## Variables

### Integer
```

Incorrect

```md
# Python

#### Integer
```

Do not skip heading levels unless there is a specific reason.

---

## 3. Add a space after the `#`

Correct

```md
# Python
```

Incorrect

```md
#Python
```

---

## 4. Keep headings short

Good

```md
## Installation
```

Better than

```md
## This Section Explains How You Can Install Python on Windows Computers
```

---

## 5. Make headings descriptive

Instead of

```md
## Topic
```

Write

```md
## Python Data Types
```

---

# Common Mistakes

## Missing Space

Incorrect

```md
#Heading
```

Correct

```md
# Heading
```

---

## Too Many `#`

Incorrect

```md
####### Heading
```

Markdown supports only **six** heading levels.

---

## Skipping Levels

Poor hierarchy

```md
# Python

#### Variables
```

Better

```md
# Python

## Variables
```

---

# Alternate Heading Syntax

Markdown also supports an older heading style.

Heading Level 1

```md
Python Notes
============
```

Output

# Python Notes

---

Heading Level 2

```md
Installation
------------
```

Output

## Installation

This style is less common today, and the `#` syntax is generally preferred because it is clearer and supports all six heading levels.

---

# Automatic Table of Contents

Many Markdown editors and GitHub use headings to automatically generate a Table of Contents.

Example

```md
# Python

## Variables

## Functions

### Lambda Functions
```

Generated structure

```
Python
├── Variables
├── Functions
    └── Lambda Functions
```

---

# Real-World Example

Consider the following README file structure:

```md
# Student Management System

## Features

## Technologies Used

## Installation

## Usage

## Project Structure

## Screenshots

## Future Improvements

## License

## Author
```

This hierarchy makes the README organized and easy to navigate for anyone viewing the project.

---

# Summary

Headings are one of the most important features of Markdown. They organize content into a clear hierarchy, improve readability, enable automatic table of contents generation, and make documents easier to maintain.

Markdown supports six heading levels, from `#` (Heading 1) to `######` (Heading 6). Following a logical heading structure and using descriptive titles helps create professional documentation that is easy to understand.

---

