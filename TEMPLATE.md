# Title #

## Subtitle \(if needed\) ## 

---------------------------------------------------

### Table of Contents ###

The table of contents is an unordered list using reference style links. Refrences should be descriptively named. Use H3 as section titles. 

  * [Basic Formatting](#Basic)

  * [Lists](#Lists)

  * [Code](#Code)

  * [Images](#Images)

  * [Task Lists](#Task)

  * [Issues](#Issues)

---------------------------------------------------

<a name="Basic"/>

### Basic Formatting ###

This is a template for all the documents in this repository in an attempt for consistent layouts. All other templates should be based off of this file.

Refer to [Github Flavored Markdown] Refer to aforementioned link for anything formatting questions not detailed in here.

Make sure all links are reference style, include references at the bottom of the section. Try to make references unique and descriptive.

Two linebreaks should be used to separate *EVERYTHING*.

Use only \*s for *italics* or **bold text**. No underscores. 

There should not be **ANY** hard tabs in this at all. 

Sections should be separated by horizontal rules. 

[Github Flavored Markdown]: https://help.github.com/articles/github-flavored-markdown    "Github Flavored Markdown"

---------------------------------------------------

<a name="Lists"/>

### Lists ###

  * Lists should be indented by 2 spaces

  * Unordered lists should use stars ONLY

  1. Ordered lists should replicate the expected order in the source.

  2. Lists should also have an empty line between them.

     New paragraphs in lists should also be indented. 

---------------------------------------------------

<a name="Code"/>

### Code ###

All code should use fenced code blocks. The language should be specified if possible. 

```C
#include <stdio.h>

int main( int argc, char* argv[] )
{
    printf("Hi! I'm a syntax highlighting example!");
}
```

--------------------------------------------------

<a name="Images"/>

### Images ###

If images are referenced, make sure they use the same syntax as the links. All images should be on their own line. 

!["Hi! I'm a penguin!"][Tux]

[Tux]: http://upload.wikimedia.org/wikipedia/commons/a/af/Tux.png   "Tux, the Linux mascot."

--------------------------------------------------

<a name="Task"/>

### Task Lists ###

Ensure that a mention is included to the person or persons, as well as an issue (if applicable). 

- [x] This task was completed by @alexschneider94
- [ ] This task needs to be completed by @alexschneider94.

--------------------------------------------------

<a name="Issues"/>

### Issues ###

TBD. Issues and pull requests use `#<number>`.
