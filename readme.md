# Welcome to the strongDM Content Style Guide

---

## NOTE This guide is a work in progress and is not currently in use in strongDM production content

---

This style guide is primarily for strongDM employees, but we hope it is helpful to other organizations as well.

This guide began as a fork of [Mailchimp's Content Style Guide](https://github.com/mailchimp/content-style-guide).

Whether or not you work at strongDM, we welcome your thoughts and suggestions. To learn more about sending us feedback or adapting this guide to create your own, see the Contributing file.

## Creating a New File

This guide is a collection of Markdown files. This is a plaintext format that easily converts to HTML. Read more about it [here](http://daringfireball.net/projects/markdown/). Be sure you name your files without spaces with either an `.md` or `.markdown` extension.

The files in this guide are prefixed with a double digit to set order. Make sure your file starts with a number that will place your new content in the desired position (eg: `04-`) and change the prefixes of the other files to reflect this change in order.

## Markdown

Markdown is handy because you can write your content without HTML tags. Here are some tips to help you control the layout of your text.

### Line Breaks

If you want a line to break to the next line but do not want to start a new paragraph, end the line with two spaces. This will render a `<br>` tag.

### Widows

The best way to prevent widows is to type `&nbsp;` in the space between the last two words in a title or paragraph.

### Tables

Tables can be written in Markdown by following this general style:

```markdown
| header 1 | header 2 |
| -------- | -------- |
| cell 1   | cell 2   |
| cell 3   | cell 4   |
```

The spacing is not important for the table to be rendered properly, and the cells do not have to line up. However it does help with readability when creating and editing tables.

### HTML Tags in Text

When displaying HTML tags as text in content, be sure to wrap them in backticks, eg: \``<h3>`\`.
