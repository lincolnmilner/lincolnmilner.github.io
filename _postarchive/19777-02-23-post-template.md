---

layout: post (only relevant layout type)
permalink: /perm/path/for/post/uri (default: /year/month/day/title.html)
published: true || false

date: YYYY-MM-DD HH24:MI:SS +/-TTTT
category/categories:
    - categoryA
    - categoryB
tags: [tag1, tag2, tag3]

custom_variable: can set custom values that are used in the page as {{ page.custom_variable }}

title: Post Title
author: Author Name

excerpt_separator: <!--more-->

---

To link to another post, you can use "post_url" followed by the filename of the post (e.g., {% post_url YYYY-MM-DD-name-of-post %})

To use it in Markdown, you would do [Name of Link]({% post_url YYYY-MM-DD-name-of-post %})
