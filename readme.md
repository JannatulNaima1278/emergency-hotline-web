1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Ans: getElementById is used to find a single element by its unique Id. getElementByClassName is used to find multiple elements by a class name. querySelector is used to find the first element matching an Id, class, tag or attribute. querySelectorAll returns a NodeList.


2.How do you create and insert a new element into the DOM?
Ans: Creating and Inserting a new DOM element involves using JavaScript:
1/ Use document.createElement('tag') to create a detached node in memory.
2/ Add content or attributes.
3/ Select an existing parent node and use a method to attach the new element, making it a live part of the DOM tree.

3.What is Event Bubbling and how does it work?
Ans: Event Bubbling is a concept in the JavaScript Event Flow where an event starts from the deepest target element an then bubbles up through its parent elements up to the top.

4.What is Event Delegation in JavaScript? Why is it useful?
Ans: Event Delegation is a technique where instead of adding event listeners to multiple child elements indivisually, you attach a single event listener to a common parent.

5.What is the difference between preventDefault() and stopPropagation() methods?
Ans: preventDefault() is used to prevent the default action of an event from being carried out by the browser. stopPropagation() is used to stop the event from propagating through the DOM tree.