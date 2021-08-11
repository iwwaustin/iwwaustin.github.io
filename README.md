### Writing Blog Posts
* Create a file in _posts of the format `YYYY-MM-DD-Post-Name.md`
* Create a metadata header at the top of that file with an appropriate list of categories/tags (please use only tags in 
  this list).
```jekyll
---
layout: post
title: "Post Name"
author: "Author Name OR Anon"
categories: 
    - Actions
    - Theory
    - Critique
    - News
    - Resources
---
```
* Write the post below the header using [Markdown formatting](https://www.markdownguide.org/basic-syntax#headings).
    * All markdown elements are supported **except** for [emoji shortcodes](https://www.markdownguide.org/tools/jekyll/)
    * link photos using the relative path `![meta-text](/assets/posts/YYYY-MM-DD-Post-Name/image-name.extension "Mouseover Text")`