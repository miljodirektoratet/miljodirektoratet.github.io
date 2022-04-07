---
layout: post
title: Bruksanvisning for nye innlegg.
description: Lånt fra Chad Baldwins Blogg (https://chadbaldwin.net/2021/03/14/how-to-build-a-sql-blog.html)
date: 2021-03-13 18:20:00 -0800
tags: Blogging
image: /img/postbanners/2021-03-13-how-to-build-a-sql-blog.png
---


* Posts are written in markdown, if you don't know it, don't worry, there's not much to it. [See this post by GitHub](https://guides.github.com/features/mastering-markdown/){:target="_blank"} to learn some of the basics.

That's about all you need to know to get started.

----

### Lets create a new blog post

1. Navigate to the `_posts` folder on GitHub
2. Click `Add file` > `Create new file`
3. Name your file `{{ site.time | date: '%Y-%m-%d' }}-your-new-blog-post.md`
4. Set the title of your blog post by using a markdown header
  * Write this as the first line `## This is my first blog post`
5. Add some content...write some random things, whatever you want
6. Throw in a code block (code blocks are created by surrounding your code snippet with three backticks at each end and an optional "language hint"), copy paste this in:
    ````plaintext
    ```tsql
    SELECT *
    FROM sys.tables
    WHERE [name] = 'SomeTable'
    ```
    ````
  * **Important note**, if you're using T-SQL code, make sure to use the `tsql` tag. This will tell your site that you want to use the SSMS style formatting.

