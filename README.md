# JS-Day-2
Progress Steps

This code is a simple implementation of a progress step indicator in HTML, CSS, and JavaScript.

1. The HTML file has a head section that contains the title of the page and the meta tags which are used to specify the character encoding and the viewport.
2. In the body section, there's a container div that holds the progress indicator. It consists of multiple circle elements that represent the steps, a progress bar, two buttons, and a script tag to include the JavaScript file.
3. The CSS file contains the styling for the progress indicator, including the font, background color, and button styles.
4. The JavaScript file uses the Document Object Model (DOM) API to access the elements from the HTML file and add event listeners to the buttons. The code uses an active class to show which step is currently active and updates the progress bar width accordingly.
5. When the Next button is clicked, the currentActive variable is incremented, and the active class is added to the corresponding circle. When the Prev button is clicked, the currentActive variable is decremented, and the active class is removed from the corresponding circle.
6. The update() function updates the active class and the width of the progress bar based on the current active step.
