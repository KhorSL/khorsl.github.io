---
layout: post
title:  "Limit characters displayed in HTML span"
date:   2019-08-06 14:45:00 +0800
categories: [html, css]
---

### Background / Context

Unlike `input` tag, `span` tag do not have the property of `maxlength`. To limit the characters in a `span` tag we need to use some CSS tricks.

#### Fix / Solution

Create a CSS class e.g. `search__result-title` and do the following:

```CSS
.search__result-title {
  display: inline-block;
  width: 70%;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}
```

#### Expected Example Result

![limit-span-tag-characters](/static/posts/2019-08-06-limit-characters-displayed-in-html-span/image/limit-span-tag-characters.png)
