---
date: "2019-05-31"
title: Styles
description: CSS Playground
tags:
- boilerplate
- css
- theme
---

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

This is an example paragraph with some **bold** text, _italic_ text,
some **_bold italic_**, as well as ~~strikethrough~~. Also some
`` `code` `` as well.

Smartypants "quotes" 1/4 and -- that's it.

    function plainAlert() {
      // based on normalize, milligram, open color, and monokailight
    }

``` html
</head>
<body>
    <div class="container">
  <header>
    <h1><a href="/">{{ .Site.Title }}</a></h1>
```

``` yaml
menu:
  main:
  - identifier: pictures
    name: Pictures
    title: Pictures
    url: /pictures/
    weight: 100

# enableGitInfo: true

pygmentsUseClasses: true
pygmentsCodefences: true

pygmentsOptions: linenos=table
#pygmentsOptions: linenos=inline, hl_lines=6-7
```

``` json
"scripts": {
  "css": "hugo gen chromastyles --style=monokailight > syntax-classes.css"
}
```

  > We also have a blockquote, and then another
  > one which is nested
  >
  >  > Within a blockquote

Here is a [Link](http://example.com/ "Optional Title") which could also be
relative, or an [internal page link](#heading-2) to headings automatically
generated id.

In practice you might do it  more like this though. I considered [Open Sans][os]
and [Source Code Pro][sc] but Roboto is good and matching family. [Feather][fi]
is something to look at.

  [os]: https://fonts.google.com/specimen/Open+Sans
  [sc]: https://github.com/adobe-fonts "Optional Title Here"
  [fi]: https://feathericons.com/
        "Or Optional Title Here"

Automatic links to <http://example.com> and <address@example.com>
with < and >.

![Alt text](/path/to/img.jpg "Optional title")

![Alt text][img1]

  [img1]: url/to/image  "Optional title attribute"

---

  * George Washington
    * John Adams
    * Thomas Jefferson
      * really not sure i like the 90% font size down the line
      * also could make everything discs, ol has no decending list-style
  * To make lists look nice, you can wrap items
    with hanging indents
  * If list items are separated by blank lines,
  
    Markdown will wrap theitems in `<p>` tags

  * A list item with a blockquote:

    > This is a blockquote
    > inside a list item.

  * A list item with a code block:

        <code goes here>

1. and ordered list of things
  1. James Madison
  2. James Monroe
  3. John Quincy Adams

First Header | Second Header
------------ | -------------:
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

You can also use html pretty much wherever