Readme from Robert L. Gorman
Robert@RobertLGorman.com

https://www.robertlgorman.com/JT_Alarm_Clock/index.htm

GitHub: https://github.com/rgaz1962/JT_Alarm_Clock


Project: 

Build an Alarm Clock. As this is an open-ended exercise, the look of the clock implementation is up to you. At a minimum your clock should:
- Display the current time.
- The ability to set an alarm. 
- Have an indication that the alarm has gone off.

I used a number of resources for different segments of the Clock and Timer as referenced below.






* Clock: 
Analog Clock using HTML, CSS and JavaScript

We are going to build a real-time analog clock using HTML, CSS, and JavaScript.


Approach: We will create three files (HTML file, a CSS file, and JavaScript File), we also have an image of the clock that will be used in the background, and on top of that, we will make an hour, minute, and second hand (using HTML and CSS). These hands will rotate as per the system time (we will use the predefined Date function of JavaScript to calculate the degree of rotations of each hand).

HTML: It is a simple file having the basic structure of the webpage and ID for the clock’s body and for the second, minute, hour hands.

CSS: The CSS is used just for making the clock actually look a bit nicer. We have basically centered our clock in the middle of the webpage.
JavaScript: The JavaScript file will provide the logic behind the rotation of the hands.
Example:

First we have selected the hour, minute, and second from HTML.
To get the current time we have used the Date() object provided by the JavaScript. This will give the current seconds, minutes, and hours respectively.
Now, we have got our hour, minute, and second, and we know that the clock rotates 360 degrees. So, we will convert to convert the rotation of the hands of the clock into degrees. The degree calculation is based on a simple unary method.


* Schedule Appointment Timer and Alarm" 






Citations:

Alarm Clock in JS | JavaScript Tutorials | Web Development Tutorials

https://youtu.be/Kcvg0jXwrvU

MDN Web Docs
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/datetime-local

Can I Use Cross-Browser Compatibility
https://caniuse.com/input-datetime

Coding Conventions
https://en.wikipedia.org/wiki/Coding_conventions

https://code-boxx.com/simple-javascript-alarm-clock/














