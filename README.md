# Uncommon HTML Bug: Accessing Non-Existent Element

This repository demonstrates a common, yet sometimes overlooked, error in HTML: attempting to access a DOM element that doesn't exist.  The bug causes a silent failure (javascript error in the console) and may lead to unexpected behavior in more complex applications.

The `bug.html` file illustrates the problem. The javascript code attempts to modify the innerHTML of an element with the ID 'nonExistentElement', which is not defined in the HTML. This can lead to errors which are not easily apparent to end-users.

The solution (`bugSolution.html`) provides a corrected version of the code. It first checks if the element exists before attempting to modify its content.  This prevents errors and ensures the application behaves as expected. 

This simple example highlights the importance of robust error handling and careful DOM manipulation in web development.