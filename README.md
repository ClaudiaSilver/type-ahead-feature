# type-ahead-feature

Based on Wes Bos's Javascript 30 project. I added/amended the following:
*   style and responsiveness through Flexbox
*   a reset button with a hover pseudoclass
*   the list of search results is now clickable: this is now a mousedown event rather than click; the first click removes focus from the input field and adds blur, therefore only the second click works)
*   on mousedown, a box appears on the right hands side
*   the content of the current target is displayed in this box
*   it is broken down into the desired chunks using regex.
*   Ta-da! 