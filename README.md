Download Link: https://assignmentchef.com/product/solved-cs141-assignment-2-geometry-calculator-and-math-tutor
<br>
<h1>Geometry Calculator</h1>




Write the program that displays the following menu:




Geometry Calculator:




<ol>

 <li>Calculate the Area of a Circle</li>

 <li>Calculate the Area of a Rectangle</li>

 <li>Calculate the Area of a Triangle</li>

 <li>Quit</li>

</ol>




Enter your choice (1 – 4):




If the user enters 1, the program should ask for the radius of the circle and then display its area. Use the following formula:

area = <sup>π</sup>r<sup>2  </sup>

Use Java constant Math.PI in your calculations.

If user enters 2, the program should ask for the length and width of the rectangle and then display the rectangle’s area. Use the following formula:

area = length * width

If the user enters 3 the program should ask for the length of the triangle’s base and its height, and then display its area. Use the following formula:  area = base * height * 0.5

If the user enters 4, the program should end.




Use Java formatting to leave no more than 2 digits after decimal point when displaying the results of calculations.




<strong><u>Input Validation</u></strong><u>:</u>

<ol>

 <li>Display an error message if the user enters number outside the range of 1 through 4 when selecting an item from the menu.</li>

 <li>Do not accept negative values for the circle’s radius, the rectangle’s length or width, or triangle’s base or height. You can use either if/else statement or an input validation loop for that purpose.</li>

</ol>

<strong> </strong>

Name your solution project Geometry.java

<strong> </strong>

<h1>Math Tutor</h1>

<strong> </strong>

Write a program that can be used as a math tutor for a young student.

The program <u>displays a menu</u> allowing the user to select an addition or subtraction problem. The final selection of the menu should let the user quit the program.




Math Tutor

<ol>

 <li>Addition problem</li>

 <li>Subtraction problem</li>

 <li>Quit</li>

</ol>

Enter your choice (1 – 4):




After the user made a choice, the program should display two <u>random</u> numbers in the range [0 – 999] to be added / subtracted, such as:

247

+  29       &lt;- –   <u>Output problem in this format.</u>

——-




The program should wait for the student to enter the answer. If the answer is correct, the message of congratulations should be printed. If the answer is incorrect, a message should be printed showing the correct answer.

Then the program should display a menu again. This process is repeated until the user chooses to quit the program.




<strong><em>Requirements: </em></strong>

<ol>

 <li>Input validation: if the user selects an item not on the menu, display an error message and display the menu again.</li>

 <li>Make sure the numbers are appearing in correct order: the top position is always occupied by the number with higher number of digits.</li>

</ol>

Sample of INCORRECT formatting:




<ol start="3">

 <li>Make sure the numbers are aligned properly when printed out as addition/subtraction problem. Use Java numeric formatting to print out numbers correctly aligned. The one-digit and two- digit numbers must be aligned well with the 3-digit numbers  For example:</li>

</ol>

247

+     8

——-




<h2>Suggested Strategy</h2>

<ol>

 <li>Start with output and numeric formatting. Use hard-coded numbers to debug the formatting part. Make sure your code displays output correctly with numbers like 23 and 345, 4 and 567, and 5 and 45 for both addition and subtraction.</li>

 <li>Add code that ensures that the larger of two numbers appears on top.</li>

 <li>Add code that enters the user answer and compares it with the correct result of addition/subtraction problem.</li>

 <li>Add code that generates two random numbers to be formatted and displayed.</li>

 <li>Add menu code with a loop and 3 possible branches – for addition and subtraction problem generation, and for quitting.</li>

</ol>


