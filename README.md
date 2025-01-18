# Uncommon HTML Bug: Incorrect DOM Manipulation
This repository demonstrates a subtle error in JavaScript when manipulating the HTML DOM. The problem lies in how the script attempts to select and modify the content of a div element. 

## Bug Description
The JavaScript code incorrectly attempts to select the element using the '#' character as part of the getElementById method's argument. This causes the script to fail silently, leaving the div element's content unchanged.

## Bug Solution
The solution shows the correct way to select the div element using getElementById and modify its content using textContent or innerHTML.