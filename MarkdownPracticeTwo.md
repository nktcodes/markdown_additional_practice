# **_Horizontal Rules_**

To create a horizontal rule, use three or more asterisks ***, three or more dashes --- or three or more underscores ____ on a line by themselves

***
---
___  

We will see three horizontal lines above as the rendered output of all three looks identical .
____________________________________________________________________________________

# **_LINKS_**

To create a link, enclose the link text in brackets [] and then follow it immediately with the URL in parentheses()

Use [Duck Duck Go](https://duckduckgo.com)

## **_Adding Titles_**

You can optionally add a title for a link.  
This will appear as a tooltip when the user hovers over the link.  
To add a title, enclose it in parentheses after the URL.

Use [Duck Duck Go](https://duckduckgo.com "My search engine!")

# **_URLS and Email Addresses_**

To quickly turn a URL or email into a link, enclose it in angle brackets <>

<https://google.com>  
<email@emailprovider.com>

# **_Formatting Links_**

To emphasize links, add asterisks before and after the brackets and parentheses.

I love supporting **[EFF](https://eff.org)**.  
This is the *[EFF](https://eff.org)*.

# **_Reference-style Links_**

Reference-style links are a special kind of link that make URLs easier to display and read in Markdown.  
Reference-style links are constructed in two parts, the part you keep inline with your text and the part you store somewhere else in the file to keep the text easy to read.

## **_Formatting the First Part of the Link_**

The first part of a reference-style link is formatted with two sets of brackets.  
The first set of brackets surrounds the text that should be linked.  
The second set of brackets displays a label used to point to the link you're storing elsewhere in your document.  
Although not required, you can include a space between the first and second set of brackets.    
Also, the label in the second set of brackets is not case sensitive and can include letters, numbers, spaces or punctuation.  
This means that the following example formats are roughly equivalent for the first part of the link

. [hobbit-hole][1]  
. [hobbit-hole] [1]  
. [hobbit-hole][a]  
. [hobbit-hole][A]  

## **_Formatting the second Part of the link_**

The second part of a reference-style link is formatted with the following attributes:

1. The label in brackets, followed immediately by a colon and at least one space, [label]: 
2. The URL for the link, which you can optionally chose in angle brackets.
3. The optional title for the link, which you can enclose in double quotes, single quotes or parentheses.


This means that the following example formats are all roughly equivalent for the second part of the link:

. [hobbit-hole]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle  
. [hobbit-hole]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit Lifestyles"  
. [hobbit-hole]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit Lifestyles"  

You can place the second part of the link anywhere in your Markdown document.  
Some people place them immediately after the paragraph in which they appear while others place them immediately at the end of the document(like endnotes or footnotes).

## **_An Example Putting the Parts Together_**

In a hole in the ground, there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit life\styles") and that means comfort.

In a hole in the ground, there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to eat: it was a [hobbit-hole][1] and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

-----------------------------------------------------------------------------


# **_Images_**

To add an image, add an exclamation mark(!), followed by alt text in brackets, and the path or URL to the image asset in parentheses.

You can optionally add a title after the URL in the parentheses.

![Tower Bridge London. A bascule and suspension bridge!]( https://img.traveltriangle.com/blog/wp-content/uploads/2019/02/Cover-for-Tower-Bridge.jpg "Tower Bridge London")


_____________________________________________________________________________

# **_Escaping Characters_**

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.

# **_Characters You can Escape_**

Backslash       \  
tickmark        `  
asterisk        *  
underscore      _  
curly braces    {}  
brackets        []  
parentheses     ()  
pound sign      #  
plus sign       +  
minus sign      -  
dot             .  
hyphen          -  
exclamation     !  

_____________________________________________________________________________

# **_EXTENDED SYNTAX_**

The extended syntax is not available in all Markdown applications.
If not, it is sometime possible to enable extensions in one's markdown processor.

_____________________________________________________________________________

# **_TABLES_**

To add a table, use three or more hyphens(---) to create each column's header
Use pipes (|) to separate the columns

|Stocks    | Prices $ |
|----------|----------|
|AAPL      |179.46    |
|TESLA     |239.76    |

Cell widths can vary but the rendered output will be the same.

| Stocks | Prices $ |
| --- | ----------- |
| AAPL | 179.46 |
| TESLA | 239.76 |

Creating tables with hyphens and pipes can be tedious.  
To save time, try using the [Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables).

## **_Alignment_**

You can align text in the columns to the left by adding a colon(:) to the left.  

You can align text in the columns to the right by adding a colon(:) to the right.

You can align text in the columns to the center by adding a colon(:) on both sides of the hyphens within the header row.

| Stocks    | Prices $    | Trend       |
| :---      | :----:      | ---:        |
| AAPL      | 179.46      | UPTREND     |
| TESLA     | 239.76      | DOWNTREND   |


## **_Formatting Text in Tables_**

You can format the text within tables.

You can add links, code(words or phrases in tick marks(`) only) and emphasis.

You cannot add headings, blockquotes, lists, horizontal rules, images or HTML tags.  

_____________________________________________________________________________

# **_Fenced Code Blocks_**

Basic Markdown syntax allows one to create code blocks by indenting lines by four spaces or 1 tab.  

If this is inconvenient, one can use fenced code blocks.  

Depending on your markdown processor, you can use three tick marks(```) or three tildes(~~~) on the lines before and after the code block.  

```
{
    "Stock" : AAPL
    "Price" : 179.46
    "Trend" : Uptrend
}
```

## **_Syntax Highlighting_**

Syntax highlighting is supported by many markdown processors in the case of fenced code blocks.

This feature allows one to add color highlighting for whatever language your code was written in.  

To add syntax highlighting, a language is specified next to the tick marks before the fenced code block.

```json
{
    "Stock" : AAPL
    "Price" : 179.46
    "Trend" : Uptrend
}
```

_____________________________________________________________________________

# **_Footnotes_**

Footnotes allow you to add notes and references without cluttering the body of a document. 

When a footnote is created, a superscript number with a link appears where you add the footnote reference. 

Readers can then click the link to jump to the content of the footnote at the bottom of the page.  

To create a footnote reference, add a caret and an identifier inside brackets [^1].  

Identifiers can be numbers or words but they can't contain spaces or tabs.  

Identifiers can only correlate the footnote reference with the footnote itself. 

In the output, footnotes are numbered sequentially.  

Examples of footnotes:


Here's a simple footnote,[^1].  

[^1]: This is the first footnote

_____________________________________________________________________________

# **_Strikethrough_**

You can strikethrough words by putting a horizontal line through their center.  

This allows you to indicate that certain words are a mistake not meant for inclusion in the document.  

To strikethrough words, use two tilde symbols(~~) before and after the words.

The price is ~~increasing~~ decreasing.

_____________________________________________________________________________

# **_Task Lists_**

Task lists allows one to create a list of items with checkboxes.  

To create a task list, add dashes(-) and brackets with a space in front of the task list items.  

To select a checkbox, add an x in between the brackets([x]).

- [x] Check Stock Prices
- [x] Check Trend
- [ ] Assess Momentum
- [ ] Initiate Algorithm


_____________________________________________________________________________

