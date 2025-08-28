# What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
getElementById - returns a single element by its unique ID.
getElementsByClassName - returns a HTMLCollection of all elements with the given class name.
querySelector - returns the first element that matches a CSS selector.
querySelectorAll - returns a NodeList of all elements matching a CSS selector.

# How do you create and insert a new element into the DOM?
I will use document.createElement('tagName') to create an element, set its content, and then use appendChild() to add it to a parent element.

# What is Event Bubbling and how does it work?
Event Bubbling is when an event starts on an element and then moves up through its parents all the way to the root, letting each one respond if it has a listener.

# What is Event Delegation in JavaScript? Why is it useful?
Event Delegation is the process of setting an event on a parent and performing various actions through its target child. This is useful because instead of writing a separate function for each child, just write one function in its parent and it will work.

# What is the difference between preventDefault() and stopPropagation() methods?
preventDefault() - This function prevents the page reloading after submitting the form.
stopPropagation() - This function prevents Event Bubbling.
