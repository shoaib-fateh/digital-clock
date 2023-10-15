# Digital Clock
This is a simple digital clock created with HTML, CSS and JavaScript. It displays the current time in a digital format (hours:minutes:seconds).

## How It Works
The clock element in HTML displays the time
A JavaScript function gets the current date/time using the Date object
It extracts the hours, minutes and seconds
leading zeros are added for values < 10
The time is displayed in the clock element by concatenating the values
The function runs every 500ms using setTimeout to update the clock

## Live Demo
You can see it working live at https://shoaib-fateh.github.io/clock-1/

## Usage
To use it, include the HTML, CSS and JavaScript files. Call the clockFunction on page load to initially display the time.
