# javascript
- Project learning Javascript

# Syntax
- document.write("Hello World");
- script tag attribute
```
<script language="javascript" type="text/javascript"><script> 
```
- External
```
 <script src="external.js"></script>
```

# Variable
```
Naming rules:
- The first character must be a letter, an underscore (_), or a dollar sign ($). Subsequent characters may be letters, digits, underscores, or dollar signs.
- Numbers are not allowed as the first character.
- Variable names cannot include a mathematical or logical operator in the name. For instance, 2*something or this+that;
- JavaScript names must not contain spaces.
```

# DOM (Document Object Model)
```
JavaScript provides a number of methods and properties for elements.
element.childNodes - returns a collection of an element's child nodes;
element.firstChild- returns the first child node of an element;
element.lastChild - returns the last child node of an element;
element.hasChildNodes - returns true if an element has any child nodes, otherwise false;
element.nextSibling - returns the next node at the same node tree level;
element.previousSibling - returns the previous node at the same node tree level;
element.parentNode - returns the parent node of an element;
```

## Working with DOM
```
Element nodes have attributes that you can get and set.
element.getAttribute(attribute) - returns the specified attribute value of an element node.
element.setAttribute(attribute, value) - sets or changes the specified attribute to the specified value.

Use the following methods to create new nodes.
element.cloneNode() - clones an element and returns the resulting node.
document.createElement(element) creates a new element node. 
document.createTextNode(text) creates a new text node.

These methods create new nodes, to which you can apply the DOM methods, but they don't appear in the document yet.

To add or remove nodes in a document:
element.removeChild(oldNode) - removes a child node from an element.
element.appendChild(newNode) - adds a new child node to an element, as the last child node;
element.insertBefore(node1, node2) - inserts node1 as a child, before node2;
element.replaceChild(newNode, oldNode) - replaces oldNode with newNode. 
```
