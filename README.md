# Uncommon HTML Error: Incorrect innerHTML Assignment with Numbers

This repository demonstrates a subtle but important error in HTML when directly assigning a number to the `innerHTML` property of an element.  While not throwing an error in many browsers, it results in unexpected behavior, usually no visible output.

The file `bug.html` shows the incorrect way, and `bugSolution.html` shows the correct way.   This issue highlights the importance of treating `innerHTML` as a string property.