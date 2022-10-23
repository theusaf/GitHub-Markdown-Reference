# About

While there are many cheat sheets already out there on the internet, they don't have everything that you can do on GitHub. This Gist intends to contain a bit more information than the others.

## GitHub Flavored Markdown

### Simple Text Formatting
```markdown
**bold**
*italics*
_italics_
~~strikethrough~~
```
**bold**<br>
*italics*<br>
_italics_<br>
~~strikethrough~~

### Headers
```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

### Links
```markdown
[Link](https://github.com)
```
[Link](https://github.com)

### Images
```markdown
![Image](https://octodex.github.com/images/Fintechtocat.png)
![Alt Text](https://example.com/nonexistent-image.png "Title")
```
![Image](https://octodex.github.com/images/Fintechtocat.png)
![Alt Text](https://example.com/nonexistent-image.png)

### Blockquotes
```markdown
> Blockquote
> > Nested Blockquote
```
> Blockquote
> > Nested Blockquote

### Lists
#### Unordered
```markdown
- List Item
* List Item
+ List Item
```
- List Item
* List Item
+ List Item

#### Ordered
```markdown
1. List Item
2. List Item
    * List Item Nested
        1. List Item Nested 2
```
1. List Item
2. List Item
    * List Item Nested
        1. List Item Nested 2

### Code
#### Inline
```markdown
`Created main loop & timing control`
```
`Created main loop & timing control`

#### Block
````markdown
```python
import antigravity

def main():
  antigravity()
```
````
```python
import antigravity

def main():
  antigravity()
```

* On the first line, you can specify the language of the code block. This will enable syntax highlighting.
* If you need to put triple backticks (or more) in your code, you can solve this by adding more backticks to the beginning and end of the code block:

  `````markdown
  ````markdown
  ```
  inner code block
  ```
  ````
  `````
* To see a list of supported languages, visit [GitHub's Linguist](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml) repo.
* You can also create diagrams: https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams

### Tables
```markdown
| Header 1 | Header 2 | Header 3 |Header 4|
| :-------- |-| :-: | --:|
| Item 1   |Item 2| Item 3   | Item 7|
| Item 4   | Item 5   | Item 6   | Item 8|
```
| Header 1 | Header 2 | Header 3 |Header 4|
| :-------- |-| :-: | --:|
| Item 1   |Item 2| Item 3   | Item 7|
| Item 4   | Item 5   | Item 6   | Item 8|

* The number of `-` is not important.
* The `:` is used to align the text in the column.
* The `|` is used to separate the columns.

### Horizontal Rule
```markdown
---
___
-----
_____
```
---
___
-----
_____
* The number of `-` or `_` is not important, as long as there are at least 3.

### Plain HTML
```html
<details>
  <summary>Click to expand!</summary>
  <p>Here is some hidden text!</p>
</details>
<u>Underlined text</u>
```
<details>
  <summary>Click to expand!</summary>
  <p>Here is some hidden text!</p>
</details>
<u>Underlined text</u>

To see the full list of HTML allowed, see [this page](https://gist.github.com/seanh/13a93686bf4c2cb16e658b3cf96807f2).

### Math/LaTeX
```markdown
$$ \sum_{i=1}^n i^3=((n(n+1))/2)^2 $$
```
$$ \sum_{i=1}^n i^3=((n(n+1))/2)^2 $$

You can also do this over multiple lines:

```markdown
$$
\begin{aligned}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{aligned}
$$
```
$$
\begin{aligned}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{aligned}
$$

Inline LaTeX is also supported like this:

```markdown
This is inline! $\sum_{i=1}^n i^3=((n(n+1))/2)^2$
```
This is inline! $\sum_{i=1}^n i^3=((n(n+1))/2)^2$

### Emojis
See: https://gist.github.com/rxaviers/7360908 or https://emoji-cheat-sheet.com
* `:octopus:` :octopus:

### Footnotes
```markdown
Here is a footnote reference,[^1][^2] and another.[^named]

[^1]: Here is a number footnote.
[^2]: Here is another number footnote.
[^named]: Here is a 'named' footnote.
```
Here is a footnote reference,[^1][^2] and another.[^named]
* Head to [bottom](#bottom) to see the footnotes.

[^1]: Here is a number footnote.
[^2]: Here is another number footnote.
[^named]: Here is a 'named' footnote.

[^1]: Here is a number footnote.
[^2]: Here is another number footnote.
[^named]: Here is a 'named' footnote.
---

## Special Markdown

### Linking lines of code
```markdown
https://github.com/theusaf/GitHub-Markdown-Reference/blob/751507eb800d337bd1cd8e09bf18d54bae615cdc/README.md#L1

https://github.com/theusaf/GitHub-Markdown-Reference/blob/751507eb800d337bd1cd8e09bf18d54bae615cdc/README.md?plain=1#L1-L5
```
Results in:
https://github.com/theusaf/GitHub-Markdown-Reference/blob/751507eb800d337bd1cd8e09bf18d54bae615cdc/README.md#L1

https://github.com/theusaf/GitHub-Markdown-Reference/blob/751507eb800d337bd1cd8e09bf18d54bae615cdc/README.md?plain=1#L1-L5

### Directives
* See https://github.com/community/community/discussions/16925
```markdown
> **Note**
> This is a note.
```

> **Note**
> This is a note.


```markdown
> **Warning**
> This is a warning.
```

> **Warning**
> This is a warning.

### Checkboxes
```markdown
- [ ] Example task 1
* [ ] Example task 2
+ [x] Example task 3
```

- [ ] Example task 1
* [ ] Example task 2
+ [x] Example task 3

<a name="bottom"></a>
