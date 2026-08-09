Offline Calculator
A simple offline calculator built with HTML, CSS, and JavaScript.

Features
Addition
Subtraction
Multiplication
Division
Clear button
Error handling for invalid expressions
Files
index.html - Contains the HTML, CSS, and JavaScript.
Dockerfile - Used to run the calculator with Docker.
How to Run
In a Browser
Download or clone the project.
Open index.html in your web browser.
Using Docker
Build the image:
docker build -t offline-calculator .
Run the container:
docker run -d -p 5580:80 offline-calculator
Open your browser and go to:
http://localhost:
Author
Lewi Yakubu
