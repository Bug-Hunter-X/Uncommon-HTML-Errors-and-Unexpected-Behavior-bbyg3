# Uncommon HTML Errors and Unexpected Behavior

This repository demonstrates a few uncommon errors and unexpected behaviors that can occur when working with HTML and JavaScript.  The examples highlight potential pitfalls and provide solutions for handling these situations.

## Bugs Demonstrated

* **Accessing Non-Existent Attributes:** Attempting to retrieve the value of an attribute that doesn't exist on an element.
* **Accessing Attributes Without Values:**  Retrieving an attribute that exists but has no value assigned to it.
* **Insecure use of innerHTML:** Illustrates a potential XSS vulnerability if user provided data is used without proper sanitization.

## Solutions

The `bugSolution.html` file provides corrected code and demonstrates how to avoid these errors, along with best practices for secure coding.