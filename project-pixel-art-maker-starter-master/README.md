Development Strategy

1 - Define variables by selecting the DOM elements that the user will interact with. This is where jQuery skills can come into play! For instance, the submit button, the table, and the color picker need to be accessed. The value of the color selected needs to be stored as well, since the clicked cell in the table needs to be set to the selected color.
2 - Add event listeners to the relevant DOM elements, so that user input can be color values and table sizes can be dynamically set by the user.
3 - Set the size of the cross stitch canvas as an N by M grid with the makeGrid() function. Use JavaScript loops to dynamically clear and create the table based on user input. Each cell should have an event listener that sets the background color of the cell to the selected color.
