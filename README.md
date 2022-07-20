Difference between document and window:
DOCUMENT:
1.	It represents any HTML document or web page that is loaded in the browser.
2.	It is loaded inside the window.
3.	It is the object of window property.
4.	All the tags, elements with attributes in HTML are part of the document.
5.	We can access the document from a window using the window. document
6.	The document is part of BOM (browser object model) and dom (Document object model)
7.	Properties of document objects such as title, body, cookies, etc can also be accessed by a window like this window. document.title
8.	syntax:
document.propertyname;
9.	example:
document.title :  will return the title of the document
WINDOW:
1.	It represents a browser window or frame that displays the contents of the webpage.   
2.	It is the very first object that is loaded in the browser.
3.	It is the object of the browser.
4.	Global objects, functions, and variables of JavaScript are members of the window object.
5.	We can access the window from the window only. i.e. window.window
6.	The window is part of BOM, not DOM.
7.	Properties of the window object cannot be accessed by the document object.
8.	syntax:
window.propertyname;
9.	example:
window.innerHeight : will return the height of the content area of the browser
