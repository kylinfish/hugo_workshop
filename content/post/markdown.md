---
title: Markdown
date: 2017-12-11T14:51:20+08:00
author: Win Yu
cover: https://images.pexels.com/photos/695992/pexels-photo-695992.jpeg?w=1260&h=750&dpr=2&auto=compress&cs=tinysrgb
categories: ["tech"]
tags: [ "markdown"]
draft: false
highlight: true
---

這裡是 Markdown 範例

<!--more-->

## @ 基礎文字格式  u, b, i

*this is in italic*  and _so is this_

**this is in bold**  and __so is this__

***this is bold and italic***  and ___so is this___


<s>this is strike through text</s>

----

## @ 標題 h1, h2, h3 ~ h6

# this is a huge header #
## this is a smaller header ##
### this is even smaller ###
#### more small ####
##### even smaller #####
###### smallest still: `<h6>` header

----

## @ 引用字段 blockquote

> Use it if you're quoting a person, a song or whatever.

> You can use *italic* or lists inside them also.
And just like with other paragraphs,
all of these lines are still
part of the blockquote, even without the > character in front.

To end the blockquote, just put a blank line before the following paragraph.  

    This line won't *have any markdown* formatting applied.
    I can even write <b>HTML</b> and it will show up as text.
    This is great for showing program source code, or HTML or even
    Markdown. <b>this won't show up as HTML</b> but
    exactly <i>as you see it in this text file</i>.

Within a paragraph, you can use backquotes to do the same thing.

`This won't be *italic* or **bold** at all.`

----

## @ 列表清單 ol, li

* an asterisk starts an unordered list
* and this is another item in the list
+ or you can also use the + character
- or the - character

To start an ordered list, write this:

1. this starts a list *with* numbers
+  this will show as number "2"
*  this will show as number "3."
9. any number, +, -, or * will keep the list going.
    * just indent by 4 spaces (or tab) to make a sub-list
        1. keep indenting for more sub lists
    * here i'm back to the second level

----

## @ 圖片 img

![alternate text](https://sourceforge.net/images/icon_linux.gif)

![PIXNET LOGO](https://upload.wikimedia.org/wikipedia/zh/5/57/Pixnet_logo.png)


----

## @ 超連結 a

<http://someurl>

<somebbob@example.com>

[連結名稱](http://someurl)


You can also put the [link URL][1] below the current paragraph
like [this][2].
   [1]: http://url
   [2]: http://another.url "A funky title"


----

```php
<?php

//Product.php

interface Product
{
    public function getProperties();
}
```



<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/highlight.js/9.12.0/styles/dracula.min.css">
<script src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/9.12.0/highlight.min.js"></script>
<script>hljs.initHighlightingOnLoad();</script>
