---
title: Markdown Syntax Guide
date: 2024-08-06
description: Tips for using basic Markdown syntax and formatting for HTML elements.
image: markdown.png
tags: 
    - markdown
    - css
    - html
    - themes
categories:
    - themes
    - syntax
---

Markdown is a simple and easy-to-use markup language you can use to format virtually any document.

As a developer, Markdown comes in handy for taking you ability to communitcate thru code to the next level.

With Markdown, it's easy to insert special characters to create headers, boldface, bullets, and so on.

This article offers a sample of basic Markdown syntax that can be used on your next project.

<!--more-->

## Headings

The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Paragraph

Headings are created by using the '#' sign.
Insert your text here under the paragraph heading to increase readibilty.

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

### Blockquote without attribution

> The quote you want to use would go here.
> **Note** that you can use *Markdown syntax* within a blockquote. Notice the **BOLD** and *Italisiced* font?

### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.


## Code Blocks
### Code block with backticks

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

### Code block indented with four spaces

    <!doctype html>
    <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

### Diff code block

```diff
[dependencies.bevy]
git = "https://github.com/bevyengine/bevy"
rev = "11f52b8c72fc3a568e8bb4a4cd1f3eb025ac2e13"
- features = ["dynamic"]
+ features = ["jpeg", "dynamic"]
```

### One line code block

```html
<p>A paragraph</p>
```

## List Types

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

* List item
* Another item
* And another item

### Nested list

* Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese

## Other Elements — sub, sup, kbd, mark

### sub - H<sub>2</sub>O 
```html
H<sub>2</sub>O
```

### sup - X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>
```html
X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>
```

### kbd - Press <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> to end the session.
```html
Press <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> to end the session.
```

### mark - Most <mark>salamanders</mark> are nocturnal.
```html
Most <mark>salamanders</mark> are nocturnal.
```

## More on Markdown

Follow this link to see the [docs](https://www.markdownguide.org/)

For more reading, see Kirk's article: [What is Markdown?](https://kirkstrobeck.github.io/whatismarkdown.com/)