# Dropdown Character Maker

## Learning Objectives

- Use a for/of loop to run a function against every item in an array (i.e., console.log , alert ).
- In response to a user event, add a new item to a state array and display the new state to the user (i.e., add a new todo).
- Use the .value property to get the value of a 'grabbed' HTML form input tag
- Use .createElement() and .append() to display a new HTML tag (with .textContent ) to a grabbed DOM element on click.
- Use .createElement() and .append() to add a list of new DOM  elements to a grabbed DOM element on click
- Create a select element to create a dropdown.
- Use `+` and `${}` to concatenate strings.
- Identify what variables are in a given scope/closure

## Live Example:

https://alchemycodelab.github.io/web-01-character-designer/

## Getting Started

User [this repository](https://github.com/alchemycodelab/half-baked-web-01-character-designer) as a template for this deliverable.


MAKE A PLAN:
- Identify any missing HTML elements/ids/classes and fill them in
- Confirm DOM elements correspond to correct HTML elements with appropriate ids/classes
- Create missing DOM elements (if there are any)
- Follow comments in JS chronologically
    // set state for how many times the user changes the head, middle, and bottom
    // set state for all of the character's catchphrases


     // get the value of the head dropdown
    // increment the head change count state
    // update the dom for the head (use style.backgroundImage on the bottomEl div instead of trying to set the .src -- it's NOT an img tag!)
    // update the stats to show the new count (call displayStats() to do this work)


    // get the value of the middle dropdown
    // increment the middle change count state
    // update the dom for the middle (NOTE: use style.backgroundImage on the middleEl div instead of trying to set the .src -- it's NOT an img tag!)
    // update the stats to show the new count (call displayStats() to do this work)


     // get the value of the bottom dropdown
    // increment the bottom change count state
    // update the dom for the bottom (NOTE use style.backgroundImage on the bottomEl div instead of trying to set the .src -- it's NOT an img tag!)
    // update the stats to show the new count (call displayStats() to do this work)


    // get the value of the catchphrase input
    // push the new catchphrase to the catchphrase array in state
    // clear out the form input's value so it's empty to the user
    // update the dom to show the new catchphrases (refactor to/call displayCatchphrases to do this work)


    // text content of the reportEl to tell the user how many times they've changed each piece of the state


    // clear out the DOM for the currently displayed catchphrases
    // loop through each catchphrase in state
    // and for each catchphrase
    // create an HTML element with the catchphrase as its text content
    // and append that HTML element to the cleared-out DOM



| Events . . .                                                                                                                                          |     |
| :---------------------------------------------------------------------------------------------------------------------------------------------------- | --: |
| Select from at least three dropdowns with at least three options each                                                                                 |   2 |
| On choosing an option from the dropdown and see the change reflected in the UI with a new image                                                       |   1 |
| On change, See all catchphrases rendered to the DOM                                                                                                   |   2 |
| When submitting a catchphrase, add it to an array of catchphrases, clear the current DOM's list of catchphrases, and list all catchphrases in the DOM |   1 |
| See displayed how many times each dropdown has been changed in the current session                                                                    |   1 |

| Functions                                                                                                                                                                                |     |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --: |
| IMPURE: `displayStats() : mutates the DOM to display a string describing the counts.` |   1 |
| IMPURE: `displayCatchphrases() : clears out the old list from the DOM, loops through catchphrases, renders and appends to the list element`                                                                                                                                                          |   2 |
