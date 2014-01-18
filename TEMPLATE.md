# Title #

## Subtitle (if needed) ##

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

### NOTE: If you have a suggestion for how a template could be improved, please discuss with the issue tracker before editing. ###

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

### Unordered Lists ###

  * Lists should be indented by 2 spaces
  * Unordered lists should use stars ONLY

### Ordered Lists ###

  1. Ordered lists should replicate the expected order in the source.
  2. Members of the same list should **NOT** have an empty line between them. 
  3. 4 spaces must occur before a newline in lists.    
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

<a name="Issues"/>

### Issues ###

TBD. Issues and pull requests use `#<number>`.
