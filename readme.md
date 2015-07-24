# MailChimp Style Guide


## Creating a New File

The files in this guide are prefixed with a double digit to establish an order to its content. Make sure your file starts with a number that will place your new content in the desired position (eg: `04-`) and change the prefixes of the other files to reflect this change in order.

Make sure you save your new file with `.html.md` as its extension. The `.html` is important for rendering in MiddleMan.

## Markdown



### Headers



### Tables

Tables can be written in Markdown by following this general style:

```markdown
| header 1 | header 2 |
| -------- | -------- |
| cell 1   | cell 2   |
| cell 3   | cell 4   |
```

The spacing is not important for the table to be rendered properly, and the cells do not have to line up. However it does help with readability when creating and editing tables.

### Frontmatter



```yaml
---
title: Intro
layout: article
---
```