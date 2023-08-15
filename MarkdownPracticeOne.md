# **_HEADINGS USING THE # SIGN_**

# H1 Heading
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading  
_____________________________________________________________________________________
# **_ALTERNATE SYNTAX FOR HEADINGS_**
**_On the line below the text, add any number of == characters for heading
level 1 or -- characters for heading level 2_**

This is also an H1 Heading
==========================
This is also an H2 Heading
--------------------------
_____________________________________________________________________________________
# **_Paragraphs_**
To create paragraphs use a blank line to seperate one or more lines of text.  
I really like markdown.  
I think I will use it more regularly.
_____________________________________________________________________________________
# **_LineBreaks_**
To create a line break, end a line with two or more spaces and then press Return  
This is line one.    
This is line two.    
This is line three.    
_____________________________________________________________________________________
# **EMPHASIS**

To make text bold, we add two asterisks or two underscores before and after a word or phrase.
To bold the middle of a word for emphasis, we add two asterisks without spaces around the letters

I love **bold text**.   
I love __bold letters__.  
Su**pe**rb
_____________________________________________________________________________________
# **_ITALICS_**
To italicize text, one asterisk or one underscore is added before and after a word or phrase.   
To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters

The *cat's meow*  
The _cat's toy_  
M*ous*e
_____________________________________________________________________________________
# Bold and Italic

To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase.

***Important Text***  
___Very Important Notice___  

You can also do as such  
__*Text*__  
**_More Text_**  

_____________________________________________________________________________________

# **BLOCKQUOTES**
To create a blockquote, we add a > in front of the paragraph
> According to Albert Einstein, mass and energy are interchangeable under certain circumstances. 

_____________________________________________________________________________________
# **BLOCKQUOTES WITH MULTIPLE PARAGRAPHS**
Blockquotes can contain multiple paragraphs.
A > is added on the blank lines in between paragraphs

> Everyone knows that paper is made from trees. But when one looks at trees, one cannot imagine that something so soft and fragile as the paper is made is so hard and strong. Plant materials such as wood are made of fibres known as cellulose. It is the primary ingredient in paper making. Raw wood is first converted into pulp consisting of a mixture of Cellulose, lignin, water and some chemicals. The pulp can be made mechanically through grinders or through chemical processes. Short fibres are produced by mechanical grinding. The paper produced in this way is weak and is used to make newspapers, magazines and phonebooks.
>
> Training in a specific branch of applied science, such as engineering, agriculture, weaving, spinning, etc., is considered technical education. It contrasts with liberal education which aims to impart general knowledge of arts and sciences. In the modern era, technical education is extremely important. Today, a country’s prosperity is determined by its industrial development. The more advanced the country is in industry, the more prosperous the country is. Technical knowledge is now the backbone of industrial progress, which holds the key to national prosperity

_____________________________________________________________________________________
# **NESTED BLOCKQUOTES**

Blockquotes can be nested.
A >> is added in front of the paragraph you want to nest

> Television is a wonderful scientific gift. It combines the advantages of cinema and radio. 
>
>> The most important and effective form of entertainment is television. It broadcasts live telecasts of major events. 

_____________________________________________________________________________________
# **BLOCKQUOTES WITH OTHER ELEMENTS**

Blockquotes can contain other Markdown formatted elements.
Not all elements can be used.
You need to experiment which ones work.

> ##### The quarterly results look great!
> - Revenue was off the charts
> - Profits were higher than ever
>
> *Everything* is **going well**

____________________________________________________________________________________
# **LISTS**
Lists can be either ordered or unordered.

## **_Ordered Lists_**
To create ordered lists, add line items with numbers followed by periods.
The numbers don't have to be in numerical order but the list needs to start with number one.

1. First item
2. Second item
3. Third item
4. Fourth item
----------------------------------------------------------------------------------------
1. First item
1. Second item
1. Third item
1. Fourth item
------------------------------------------------------------------------------------
1. First item
3. Second item
5. Third item
8. Fourth item
------------------------------------------------------------------------------------
## **_Nesting Lists_**

1. First item
2. Second item
3. Third item
   1. First Indented item
   2. Second Indented item
   3. Third Indented item
4. Fourth item
5. Fifth item
6. Sixth item
------------------------------------------------------------------------------------
## **_Unordered Lists_**

To create an unordered list, we add the following in front of line items:  
add dashes -
add asterisks *
add plus signs +

* Item One
* Item Two
* Item Three

- Item One
- Item Two
- Item Three

+ Item One
+ Item Two
+ Item Three

------------------------------------------------------------------------------------
## **_Nesting Unordered Lists_**

To nest items in an unordered list, we indent the items four spaces/1 tab 

* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2
* Item 4
* Item 5

## **_Adding Elements in Lists_**

#### **_Paragraphs_**

To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab.

* This is item one
* This is item two  
    Adding another paragraph here
* This is item three

#### **_Blockquotes_**

* This is item one
* This is item two
    > A blockquote is added like this
* This is item three

____________________________________________________________________________________

# **_Code Blocks_**

Code Blocks are normally indented four spaces or one tab.
When they are in a list, indent them eight spaces or two tabs.

1. Open the file  
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>
          
3. Update the title to match the name of your website

____________________________________________________________________________________

# **_Images_**
Indent four spaces or one tab

1. Open the file containing Tux, the Linux mascot.
2. Marvel at its beauty.

    ![Tux](https://upload.wikimedia.org/wikipedia/commons/a/af/Tux.png)
3. Close the file.

------------------------------------------------------------------------------------

# **_CODE_**

_To denote a word or phrase as code, enclose it in tick marks `_

At the command prompt, type `nano`

------------------------------------------------------------------------------------

# **_Escaping Tick Marks_**

If the word or phrase you want to denote as code includes one or more tick marks,
you can escape it by enclosing the word or phrase in double tick marks ``

``Use `code` in your markdown file.``

------------------------------------------------------------------------------------

# **_Code Blocks_**

To create code blocks, indent every line of the block by at least 4 spaces or one tab

    <html>
      <head>
      </head>
    </html>
    
____________________________________________________________________________________

