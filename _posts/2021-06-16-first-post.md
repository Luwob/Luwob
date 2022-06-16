# This is my first blog post

This is a test to se how things work.

### Writing paragraphs
Paragraphs are done by leaving a blank line between lines containing text!

### Writing footnotes
Footnotes are easily done using `[^number-here]` and numbering it accordingly. 

Example 1[^1]

Example 2[^2]

Example 3[^example]

You can also use words to make the coding more easy to understand, and github will make it show like a number. e.g. `[^description-here]`

After the text, just use the `[^number-here]` you used and write the text/links:

[^1]: Just an example here.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^example]:
    Here we are using named notes to make easy to identify the footnote while coding/writing!
    You can do multiple lines just by leaving four spaces before the text in each line.

Also, footnotes render in the end of the page, always!

e.g.
```
Example 1[^1]
[^1]: Just an example here.
```

### Hiding comments from rendering
You can hide comments from rendering by using this format: `<!-- Your hidden comment goes here -->`.
<!-- this comment its hidden ;) -->

### Formatting 
You can check all the formatting symbols used by [clicking here](https://daringfireball.net/projects/markdown/syntax#backslash).

- We use a single asterisk or a single underscore to make a *italic* formatted word: `*italic*`
- We use double asterisks or double underscores to make a **bold** formatted word: `**bold**`

### Ignore markdown formatting
Sometimes we want to type something but the markdown think it is a code. To prevent this, use a backslash before the symbol you want: `\*`. 
Like in *here* we have a italic formatted word. But we want to show the star symbol, so, \*here\* it is.  

### Code blocks
Code blocks work by using threee backticks before and after the codeblock, and also a language hint after the three first backticks to indicate to github to format according to a specific language.

Writing a Code block using a language hint indicating to github to use SSMS style formatting for TSQL:
e.g.:

 ```tsql
 SELECT *
 FROM sys.tables
 WHERE [name] = 'SomeTable'
```

Or a python example using a codeblock and indicating to github to use SSMS style formatting for Python:

```python
import numpy as np
pi = np.pi
print(f' Pi = {pi:.4f}')
```

The same code, but, without indicating to github to format the code style (it looks kinda boring tho):

```
import numpy as np
pi = np.pi
print(f' Pi = {pi:.4f}')
```

### Inline code
And here we use some `inline code`. We use the ` backtick ` symbol (acento `crase`, em português) between the command/code/word we want to highlight.


# NEW H1 HEADER
A title can be done using ONE hashtag `#`symbol followed be a single backspace and then the title you want to use.
This is the biggest header possible!

e.g.:`# YOUR HEADER H1`
Also you can use this way:

```
Header H1
=====

```

## NEW H2 HEADER

e.g.:`## YOUR HEADER`

Or, even:
```
Header H2
-----
```
### NEW H3 HEADER
Titles does not have the line separating it from the incoming text like headers do!

e.g.:`### YOUR TITLE`

#### NEW H4 HEADER

e.g.:`#### YOUR H4 HEADER`

##### NEW H5 HEADER
e.g.:`##### YOUR SUBSUBTITLE`

###### NEW H6 HEADER
e.g.:`###### YOUR SUBSUBTITLE`

### Use of Quotations
To do quotations we just use `> quotationhere`.
e.g.:
> This is a quotation.

### Links
Links like https://www.google.com can be written inline like [this](google.com) by using this format: 
`[word or phrase you want](www.the-website-you-want.com)`

### Implicit links
A very cool function is to use implicit links. Check out this:

Using the implicit link name shortcut, you could instead write:

-> I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"
  
This magic was done this way: 
```
I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"
```

### Relative links
Even cooler, you can point to relative links in the same repository of your github website (in its root)!
Just need to write it like this:
`[Contribution guidelines for this project](docs/CONTRIBUTING.md)`

### Images
To place images, just use a exclamation mark before its link like this:

`![the image description/alternative text](www.the-image-you-want.com/theimageyouwant.png)`

It will show up like this:

![My profile picture](https://avatars.githubusercontent.com/u/91208601?s=40&v=4)

### Making lists

Lists can be done just by using `-` , `*` or `.` before the text. You can enumerate them using a numberbefore the symbol:

- item one
- item two
- item three

1. item one
2. item two

Note that `-`, `*`and `+` does produce the same bulletpoints style:

- item one
- item two
- 
* item one
* item two

+ item one
+ item two

#### Nested lists
Nested lists are also easily done. You must press the space bar until the `-` is behind the first letter of the upper item in the list:
```
1. Item one
   - nested item
   - nested item
     - even more nested item 
```

1. Item one
   - nested item
   - nested item
     - even more nested item 

#### Marked lists
Even cooler, and easier, are mark lists. Just use `[ ]` to a empty box or `[x]` (with a lowercase x) for a marked box before the text of the item (and after the list symbol):
```
- [x] drink water
- [ ] cook pasta
```

- [x] drink water
- [ ] cook pasta

### Emojis
You can use emojis like :grin: by placing its emoji code between : `:EMOJICODE:`
To check available emoji codes, [click here](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)!






More tips to writing in markdown: [go here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
