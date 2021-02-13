# Problem Domain, Objects, and the DOM:

## What is Object ??
set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.

- IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES :Properties te ll us about the object.

- IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS ,Methods represent tasks that are associated with the object.

Example :

![Pic1](t52ni02srb8688lh3eh8.png)



## Programmers use a lot of name/value pairs:

- **HTML** uses attribute names and values.

- **CSS** uses property names and values. 

- In **JavaScript**: Variables have a name and you can assign them a value of a string, number, or Boolean.

- **Arrays** have a name and a group of values. (Each item in an array is a name value pair because it has an index number and a value.)

- **Named functions** have a name and value that is a set of statements to run if the function is called.
- **Objects** consist of a set of name/value pairs (but the names are referred to as keys).



# chapter 5 : Document Object Model (DOM)


![pIC2](5014339ce7.png)


**(DOM)** specifies how browsers should create a model of an HTML page and how JavaScript can access and update the
contents of a web page while it is in the browser window.

When the browser loads a web page, it creates a model of the page in memory.

The **DOM** specifies the way in which the browser should structure this model using a **DOM tree.**

The **DOM** is called an object model because the model (the DOM tree) is made of objects.



## THE DOM TREE IS A MODEL OF A WEB PAGE

It consists of four main types of nodes:
- THE DOCUMENT NODE.

- ELEMENT NODES.

- ATTRIBUTE NODES.

- TEXT NODES.



![Pic3](1200px-DOM-model.svg.png)


## ACCESSING ELEMENTS
**DOM** queries may return one element, or they may return a Nodelist,
which is a collection of nodes.

## METHODS THAT RETURN A SINGLE ELEMENT NODE:4

- getElementByld`('id')`

- querySelector`( 'css selector')`

- getElementsByClassName`('class')`

- getElementsByTagName`('tagName')`

- querySelectorAll `( 'css selector' )`


## what is the queries?
queries are methods that find elements in the **DOM** tree.
queries return one element, or they may return a Nodelist. Nodelist is a collection of nodes , so when a method returns more than one node, and always return a Nodelist, which is a collection of nodes even if it only finds one matching element.

Finding the quickest way to access an element within your web page will make the page seem faster and/or more responsive.

## to select indivisual elements we use this methods :
 getElementById() ,querySelector(). to selcting an elment from a Nodelist : ` item()`, array synatx. repeating actions for an entir nodelist : Loop through every node in the collection and apply the same statment to each.
adding or removing HTML content:
`the innerHTML proparty`
**DOM** manipulation methods -From an element node, you can access and update its content using properties such as textContent and innerHTML or using **DOM** manipulation techniques.

Browsers offer tools for viewing the **DOM** tree browsers, implementation of the DOM is inconsistent, and is a popular reason for using jQuery.the element node can contain multiple text nodes and child elements that are siblings of each other.









