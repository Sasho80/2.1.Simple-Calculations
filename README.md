01.Problem:Square Area
This code demonstrates how we can calculate the square area by the given length of the side.

02.Problem:Converting Inches into Centimeters
Let's write a program that reads a floating-point number in inches and converts it to centimeters.

03.Problem:Greeting by Name
Let's write a program that asks the user for their name and salutes them with the text "Hello, <name>!"

04.Problem:Concatenating Text and Numbers
Besides for summing up numbers, the operator + is also used for joining pieces of text (concatenation 
of two strings one after another). In programming, joining two pieces of text is called "concatenation". 
Here is how we can concatenate a text with a number by the + operator.

05.Problem: Calculating Trapezoid Area
Let's write a program that inputs the lengths of the two bases of a trapezoid and its height (one 
floating point number per line) and calculates the area of the trapezoid by the standard math formula:
area=(b1+b1)*h/2.0.

06.Problem: Circle Area and Perimeter
Let's write a program that calculates a circle area and perimeter by reading its radius r. Formulas:
• Area = π * r * r
• Perimeter = 2 * π * r
• π ≈ 3.14159265358979323846…

07.Problem: 2D Rectangle Area
A rectangle is given with the coordinates of two of its opposite 
angles. Calculate its area and perimeter (see the screenshot).
In this task, we have to consider that if we subtract the smaller
x from the bigger x, we will obtain the length of the rectangle. 
Identically, if we subtract the smaller y from the bigger y, we 
will obtain the height of the rectangle. What is left is to multiply 
both sides.

08.Problem: Triangle Area
Write a program that reads from the console a side and height of a triangle and calculates its area. 
Use the formula for triangle area: area = a * h / 2. Round the result to 2 digits after the decimal point 
using fixed << setprecision(2),by including the library <iomanip>).
  
Sample Input and Output   
Input Output              Input Output                 Input Output                 Input   Output 
20                        15                           7.75                         1.23456
30   Triangle area = 300  35    Triangle area = 262.5  8.45  Triangle area = 32.74  1.23456 Triangle area = 2.82  
  
09.Problem: Converter – from °C Degrees to °F Degrees
Write a program that reads degrees on Celsius scale (°C) and converts them to degrees on Fahrenheit 
scale (°F). Look on the Internet for a proper formula to do the calculations. Round the result to 2 digits 
after the decimal point.
Here are a few examples:
Sample Input and Output
Input Output Input Output Input Output Input Output 
25    77     0     32     -5.5  22.1   32.3  90.14
 
10.Problem: Converter – from Radians to Degrees
Write a program, that reads an angle in radians (rad) and converts it to degrees (deg). Look for a 
proper formula on the Internet. The number π in C# programs is available through Math.PI. Round 
the result to the nearest integer using the function <cmath>,which is located in
the <cmath> library.
  
Sample Input and Output 
Input  Output Input  Output 
3.1416 180    0.7854 45 
6.2832 360    0.5236 30
  
11.Problem: Converter – USD to BGN
Write a program for conversion of US dollars (USD) into Bulgarian levs (BGN). Round the result to 2 
digits after the decimal point, like it is shown at the examples below. Use a fixed rate between a dollar
(USD) and levs (BGN): 1 USD = 1.79549 BGN.
 
Sample Input and Output
Input Output    Input Output     Input Output 
20    35.91 BGN 100   179.55 BGN 12.5  22.44 BGN
  
12.Problem: * Currency Converter
Write a program for conversion of money from one currency into another. It has to support the 
following currencies: BGN, USD, EUR, GBP. Use the following fixed currency rates:
Rate USD EUR GBP 
1 BGN 1.79549 1.95583 2.53405
The input is sum for conversion, input currency and output currency. The output is one number – the 
converted value of the above currency rates, rounded 2 digits after the decimal point.
Sample Input and Output
Input Output    Input Output    Input    Output     Input  Output
20    35.91 BGN  100   51.13EUR 12.35    9.53 GBP   150.35 138.02 EUR
USD              EUR            EUR                 USD
BGN              BGN            GBP                 EUR
 

