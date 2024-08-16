Shopping List Example
This is a simple shopping list web application built using HTML, CSS, and JavaScript. The application allows users to add and remove items from a shopping list.

Features
Add Item: Users can type an item into the input field and add it to the list by clicking the "Add item" button.
Remove Item: Each item in the list has a "Delete" button that allows users to remove the item from the list.
File Structure
index.html: The main HTML file containing the structure of the page.
style: Contains the CSS styles for the list and buttons.
script: JavaScript functionality for adding and removing items from the list.
How to Use
Open the index.html file in a web browser.
Enter an item in the input field.
Click the "Add item" button to add the item to the shopping list.
To remove an item, click the "Delete" button next to the item in the list.
Code Overview
The HTML structure contains:

A heading (<h1>) for the title.
A text input (<input type="text">) for entering new items.
A button (<button>) to add the entered item to the list.
An unordered list (<ul>) to display the items.
The CSS styles:

Define spacing and appearance of the list items and buttons.
The JavaScript:

Selects the necessary elements (<ul>, <input>, <button>).
Adds an event listener to the "Add item" button to add a new item to the list.
Creates new list items dynamically with a "Delete" button.
Adds an event listener to the "Delete" button to remove the item from the list.
Dependencies
This project does not have any external dependencies. It only uses plain HTML, CSS, and JavaScript.

Browser Compatibility
The application is compatible with all modern web browsers that support HTML5, CSS3, and JavaScript.