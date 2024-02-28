# Comprehensive Markdown Example

## Table of Contents
- [Comprehensive Markdown Example](#comprehensive-markdown-example)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [C Code Snippet](#c-code-snippet)
  - [Mathematical Formula (Paragraph)](#mathematical-formula-paragraph)
  - [Mathematical Formula (In-line)](#mathematical-formula-in-line)
  - [Images](#images)
  - [Images in HTML](#images-in-html)
  - [Links](#links)
  - [Tables](#tables)
  - [Lists](#lists)
  - [Task Lists](#task-lists)
  - [Blockquotes](#blockquotes)
  - [Inline HTML](#inline-html)
  - [Footnotes](#footnotes)

## Introduction

This document serves as a comprehensive example of various markdown features including code snippets, mathematical formulas, images, links, and tables. Markdown is a lightweight markup language with plain-text formatting syntax that can be converted to HTML and many other formats.

## C Code Snippet

Below is an example of a simple C code snippet that prints "Hello, World!" to the console.

```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

## Mathematical Formula (Paragraph)

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

## Mathematical Formula (In-line)
Einstein's formula: $E=mc^2$ 🎉

## Images

![Cat](https://thumbs.dreamstime.com/b/random-cat-love-cats-pet-catsslave-110819582.jpg "Meow")

## Images in HTML
<img src="https://thumbs.dreamstime.com/b/random-cat-love-cats-pet-catsslave-110819582.jpg" alt="Cat" width="100" height="100">

## Links

Click here to visit [JumpFast Technologies](https://www.jumpfast.tech "JumpFast")

## Tables
Here's a table.
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1, Column 1 | Row 1, Column 2 | Row 1, Column 3 |
| Row 2, Column 1 | Row 2, Column 2 | Row 2, Column 3 |
| Row 3, Column 1 | Row 3, Column 2 | Row 3, Column 3 |

## Lists

1. Make my changes
    1. Fix bug
    2. Improve formatting
        - Make the headings bigger
2. Push my commits to GitHub
3. Open a pull request
    + Describe my changes
    + Mention all the members of my team
        * Ask for feedback

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    * Facilisis in pretium nisl aliquet
    * Nulla volutpat aliquam velit
+ Very easy!

## Task Lists

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [ ] this is a complete item
- [ ] this is an incomplete item

## Blockquotes

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.

## Inline HTML

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

## Footnotes

Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.
