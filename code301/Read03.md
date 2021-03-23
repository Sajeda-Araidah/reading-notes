
# Javascript Templating Language and Engine— Mustache.js with Node and Express
## Javascript Templating
Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.

The template engine then replaces variables and instances declared in a template file with actual values at runtime, and converts the template into an HTML file sent to the client.

 

## Mustache

As the name suggests, it was named mustache because the syntax resembles a Mustache. E.g. {{ placeholder }}
Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.

It is often referred to as “logic-less” because there are no if statements, else clauses, or for loops. Instead, there are only tags. Some tags are replaced with a value, some nothing, and others a series of values.

 

## Guide to Flexbox
### CSS Flexbox Layout Module
Before the Flexbox Layout module, there were four layout modes:

- Block, for sections in a webpage
- Inline, for text
- Table, for two-dimensional table data
- Positioned, for the explicit position of an element
The Flexible Box Layout Module makes it easier to design a flexible responsive layout structure without using float or positioning.

 

## justify-content
![pic](https://css-tricks.com/wp-content/uploads/2018/10/justify-content.svg)
flex items within a flex container demonstrating the different spacing options

This defines the alignment along the main axis. It helps distribute extra free space leftover when either all the flex items on a line are inflexible, or are flexible but have reached their maximum size. It also exerts some control over the alignment of items when they overflow the line.

.container {
  justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right ... + safe | unsafe;
}
**flex-start** (default): items are packed toward the start of the flex-direction.

**flex-end:** items are packed toward the end of the flex-direction.

**start:** items are packed toward the start of the writing-mode direction.

**end:** items are packed toward the end of the writing-mode direction.

**left:** items are packed toward left edge of the container, unless that doesn’t make sense with the flex-direction, then it behaves like start.

**right:** items are packed toward right edge of the container, unless that doesn’t make sense with the flex-direction, then it behaves like end.

**center:** items are centered along the line

**space-between:** items are evenly distributed in the line; first item is on the start line, last item on the end line

**space-around:** items are evenly distributed in the line with equal space around them. Note that visually the spaces aren’t equal, since all the items have equal space on both sides. The first item will have one unit of space against the container edge, but two units of space between the next item because that next item has its own spacing that applies.


**space-evenly:**items are distributed so that the spacing between any two items (and the space to the edges) is equal.
 