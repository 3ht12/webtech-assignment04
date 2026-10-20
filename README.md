# Web Technologies - Assignment 04
Student Name: Rana Ehtisham Adeel
Roll Number:  BITF24A041

## Project Description
This is a frontend only Slides Application built using basic HTML, CSS, and JavaScript. It allows the user to write slides in Markdown format, preview them live, save them to the browser's local memory, and present them in a separate window.

## Features Implemented
*   **Live Preview:** Left side is for typing Markdown, right side shows the live preview.
*   **Slide Separation:** Uses `---` to separate slides.
*   **Local Storage:** Saves the markdown data so it doesn't get lost when the browser is closed.
*   **Navigation:** Left and Right buttons to change slides. They disable when you reach the start or end.
*   **Keyboard Shortcuts:** Arrow keys for navigation, F11 for fullscreen, and Ctrl+S for saving.
*   **Slide Counter:** Shows "Current Slide / Total Slides" at the bottom.

## Known Issues / Limitations
I am still learning JavaScript, so there are a few bugs in the code:
1.  The browser's default save dialog still pops up when I press `Ctrl+S` because I could not figure out how to use `preventDefault` properly.
2.  When I press `Esc` to exit fullscreen, the button text doesn't change back to "Full Screen".
3.  The Markdown parser I wrote is very basic and only handles `#` headings. It doesn't perfectly format everything.
4.  If the text area is empty, the slide counter shows "1 / 0".

I tried my best to implement all the required features, but I struggled a bit with the JavaScript logic.

## How to Use
1. Open `index.html` in your browser.
2. Write your markdown in the left box (Use `#` for titles and `---` for new slides).
3. Click **Save** or press `Ctrl+S`.
4. Click **Present** to open the presentation screen.
