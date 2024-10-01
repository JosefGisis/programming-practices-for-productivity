# Markdown Guide

This file is my guide to markdown syntax (it follows the Learn new skills rule ). It is based on Darsaveli's Readme Markdown Syntax repo. Check out <https://github.com/darsaveli/Readme-Markdown-Syntax?tab=readme-ov-file#fenced-code-blocks>

---

## Headers

```md
# Heading1

## Heading2

### Heading3

#### Heading4

##### Heading5

###### Heading6
```

# Heading1

## Heading2

### Heading3

#### Heading4

##### Heading5

###### Heading6

### Font Styles

---

## Font Styles

```md
_Italics_
_Also italics_
**Bold**
**Also bold**
**_Bold and italics_**
_also italics and **bold**_
~~Striked text~~
```

_Italics_

_Also italics_

**Bold**

**Also bold**

**_Bold and italics_**

_also italics and **bold**_

~~Striked text~~

---

## Bulleted Lists

For unordered lists

```md
-   item1
-   item2
    -   subitem 1-1
    -   subitem 1-2
        -   subitem 1-2-1
        -   subitem 1-2-2
```

-   item1
-   item2
    -   subitem 1-1
    -   subitem 1-2
        -   subitem 1-2-1
        -   subitem 1-2-2

For ordered lists

```md
1. first
2. second
    1. third
    2. four
        1. five
        2. six
```

1. first
2. second
    1. third
    2. four
        1. five
        2. six

### Links

-   [Link with more info with various formatting options](https://docs.github.com/en/github/writing-on-github 'more info')
-   https://www.google.com/
-   <https://www.google.com/>

##### Link Labels: [My link label][the actual link]

##### Links to a url in the repo: [Example document](/example/example.md)

### Inserting Images

![alt](URL 'title')

-   alt takes the place of the image if it cannot be diplayed
-   parenthesis contains image source
-   title in quotes indicates the text to display when the mouse hovers over the image (can be omitted)

![extremely menacing chick](/20221106_001445.jpg 'an extremely menacing chick')

##### Resizing

<img src="/20221106_001445.jpg" alt='a smaller image of an extremely menacing chick' width="20%" height='auto'/>

### Tables

| Header1 | Header2 | Header3 |
| ------- | ------- | ------- |
| This    | is row  | 1       |
| This    | is row  | 2       |
| This    | is row  | 3       |

##### Table Alignment

| Align left |    Centered     | Align right |
| :--------- | :-------------: | ----------: |
| col 3 is   | some wordy text |       $1600 |

### Checkboxes

[ ] non-checked checkbox
[x] checked checkbox

### Quoting Text

> Block quoted text

##### Mutli-level block quotting

> Quote 1
>
> > Quote 2
> >
> > > Quote 3
> > >
> > > > Quote 4

### Text Highlighting

`This text has a glow-up`

### Horizontal Line

`___`

`***`

---

<hr>

### Line Break

<br>

### Markdown escape

```git
 * __ <br> etc
```

### Multi-line text

    this should be a multi-line
    text block.

### MD Comments

<!-- This is a markdown comment -->

### Emojis

:poop:

### Code blocks

single backtick
whitespace
fourspace
three backticks

```js
console.log('javascript')
```

```python
print('python')
```

```java
System.out.println('java')
```

```json
{
	"firstName": "A",
	"lastName": "B",
	"age": 18
}
```

### Diff Syntax

```diff
+ added this bit of code
- removed this bit of code
```