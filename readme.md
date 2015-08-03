# MailChimp Style Guide


## Creating a New File

The files in this guide are prefixed with a double digit to establish an order to its content. Make sure your file starts with a number that will place your new content in the desired position (eg: `04-`) and change the prefixes of the other files to reflect this change in order.

Make sure you save your new file with `.html.md` as its extension. The `.html` is important for rendering in MiddleMan.

## Markdown

Markdown is handy because you can write your content without HTML tags. However this can leave you with few options if you want to control the layout of your text.

### Headers

The `h1` of every page is generated from the `title` key in Frontmatter. All headers in article content should start at `h2`.

### HTML Tags in Text

When displaying HTML tags as text in content, be sure to wrap them in backticks, eg: \`<h3>\`.

### Tables

Tables can be written in Markdown by following this general style:

```markdown
| header 1 | header 2 |
| -------- | -------- |
| cell 1   | cell 2   |
| cell 3   | cell 4   |
```

The spacing is not important for the table to be rendered properly, and the cells do not have to line up. However it does help with readability when creating and editing tables.

### Line Breaks

If you want a line to break to the next line but don't want to start a new paragraph, end the line with two spaces. This will render a `<br>` tag.

### Widows

The best way to prevent widows is to type `&nbsp;` in the space between the last two words in a title or paragraph.

## Frontmatter

At the top of each file is a set of information that isn't directly displayed on a page. The title of the article is set by the `title:` key and the template is set by `layout:`.

```yaml
---
title: Intro
layout: article
---
```

If the page is going to be an outbound link (eg: [voiceandtone.com](http://voiceandtone.com)) this can be set by a `url:` key in Frontmatter.