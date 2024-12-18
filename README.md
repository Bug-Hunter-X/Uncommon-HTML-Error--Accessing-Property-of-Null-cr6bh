# Uncommon HTML Error: Accessing Property of Null

This repository demonstrates a subtle error in HTML/JavaScript that can be difficult to track down. The error occurs when attempting to access a property of an element that doesn't exist, resulting in a null reference error.

The `bug.html` file demonstrates the problem. The script tries to access a non-existent property of an element found using `getElementById`, which will return null if the element isn't found. This causes a runtime JavaScript error.

The `solution.html` file demonstrates a solution using conditional checking to avoid the error.