# Chapter 2 : Text 

## HEADING

### HTML has six "levels" of headings:

`<h1>` 
 # This is a Main Heading

`<h2>`
## This is a Level 2 Heading

`<h3>`
### This is a Level 3 Heading

`<h4>`
#### This is a Level 4 Heading 

`<h5>`
##### This is a Level 5 Heading

`<h6>`
###### This is a Level 6 Heading

## PARAGHAPH

`<p>` paragraph consists of one or more sentences
that form a self-contained unit of discourse. The
start of a paragraph is indicated by a new
line tag.paragraph consists of one or more sentences
that form a self-contained unit of discourse. The
start of a paragraph is indicated by a new
line tag.paragraph consists of one or more sentences
that form a self-contained unit of discourse. The
start of a paragraph is indicated by a new
line tag.paragraph consists of one or more sentences
that form a self-contained unit of discourse. The
start of a paragraph is indicated by a new
line tag.`</p>` 

## BOLD AND ITLAIC

`<b>` **we can make characters appear bold** `</b>`

`<i>` _we can make characters appear italic._`</i>`

## SUBSCRIPT & SUPSCRIPT

`<sup>` element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 22.
`<sub>`
The `<sub>` element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas such as H20.

`<br />` new line

`<hr />`
To create a break between

themes such as a change of

 you can add a horizontal rule between sectionsusing the `<hr />` tag.


 # Introduction to CSS 

 ## A CSS rule contains two parts: a selector and a declaration.
 ![Pic1](css.PNG)


 Declarations indicate how the elements referred to in the selector should be styled.Declarations are split into two parts (a property and a value),and are separated by a colon.

# We Can use CSS In :
```Selectors```  indicate which element the rule applies to. 
```Declarations```  indicate how the elements referred to in the selector should be styled.Declarations are split into two parts (a ```property``` and a ```value```),and are separated by a colon.

## We Can use CSS In :
```Inline ``` : It's  used to apply css style for a one element.
```Internal ``` : ```style``` You can also include CSS rules within an HTML page by placing them inside a style element
``` External``` : The ```link``` element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the ```head``` element.It should use three attributes:
 ```href``` ,```type```,  ```rel```

# CSS Selectors : 
There are many different typesof CSS selector that allow you to target rules to specific elementsin an HTML document.

|Selector| Meaning |Example|

| --- | --- |

|```Universal Selector```|Applies to all elements in the document|* { } Targets all elements on the page|

|```Type Selector```|Matches element names|h1, h2, h3  { } Targets the <h1>, <h2> and <h3> elements|

|```Class Selector```|Matches an element whose class attribute has a value thatmatches the one specified after the period (or full stop) symbol|.note { } Targets any element whose class attribute has a value of note |

|```ID Selector```|Matches an element whose id attribute has a value that matches the one specified afterthe pound or hash symbol|#introduction { } Targets the element whose id attribute has a value of introduction|
