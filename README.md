# **Scientific Calculator and Graph Plotter**
## **Overview**

A desktop application combining a scientific calculator with a function graphing tool, built using Python and Tkinter.

## Screenshots:

- ## **Calculator Interface**
  ![image](https://github.com/user-attachments/assets/674255c2-ed9c-42d5-88b5-feeaa0f0ca3b)
- ## **Graph Plotter Interface**
  ![image](https://github.com/user-attachments/assets/b9edc096-094d-4ba6-990a-96344b85bca9)
- ## **Sin(x) Graph**
  ![image](https://github.com/user-attachments/assets/8fef0629-4af9-4581-b3c9-39f63e263139)
- ## **Tan(x) Graph**
  ![image](https://github.com/user-attachments/assets/5769f413-8d48-40a8-af04-43d3e2a79d7d)

## **Installation**

1.	Ensure you have Python 3.x installed on your system
2.	Install required libraries using pip: 
pip install tkinter numpy matplotlib sympy
3.	Download the “Scientific Calculator and Graph Plotter.py” python file from github page
https://github.com/Anujkaushik01/Scientific-Calculator-and-Graph-Plotter-/blob/1.0/Scientific%20Calculator%20and%20Graph%20Plotter.py
4.	Then run the python file as following:
python scientific_calculator.py

**Alternatively**

1.	Download the exe file or linux application file from github releases page:
https://github.com/Anujkaushik01/Scientific-Calculator-and-Graph-Plotter-/releases/tag/1.0
2.	Run the application by double clicking in Windows 
3.	Or In Linux terminal run:
./Scientific_Calculator_and_Graph_Plotter_Linux

## **Features**

- Advanced scientific calculator with:
   - Trigonometric functions (sin, cos, tan, cot)
   - Logarithmic functions
   - Exponential calculations
   - Factorial and percentage calculations

- Interactive graph plotting
- Switchable calculator and graph interfaces

## **Using the Scientific Calculator**

**Basic Operations**
1.	Enter numbers using the number pad (0-9)
2.	Use operation buttons (+, -, *, /) to perform basic arithmetic
3.	Press '=' to calculate the result
4.	Press 'AC' to clear all input
5.	Press 'DEL' to delete the last character

**Advanced Functions**

•	**Trigonometric Functions:**
o	sin: Calculate sine of an angle
o	cos: Calculate cosine of an angle
o	tan: Calculate tangent of an angle
o	cot: Calculate cotangent of an angle

Note: All trigonometric functions use degrees by default.

•	**Logarithmic Functions:**
o	log₁₀: Calculate base-10 logarithm
o	ln: Calculate natural logarithm

•	**Power and Root Functions:** 
o	x²: Square the current value
o	x³: Cube the current value
o	x^n: Raise to a custom power
o	√: Square root
o	³√: Cube root

•	**Other Functions:** 
o	abs: Absolute value
o	x!: Factorial
o	±: Change sign
o	EXP: Scientific notation (×10ⁿ)

•	**Constants:** 
o	π: Pi (3.14159...)
o	e: Euler's number (2.71828...)

**Note:** To calculate any functional value, first input the value and then press the desired function. 
For example: If you want to calculate sin(90) then first input the value 90 in calculator and the press sin function, this will return the desired value.
Using the Graph Plotter

## **Plotting a Function**
1.	Enter your function in the "y =" field
 - Use 'x' as the variable
 -	Example functions:
 -	x^2 (parabola)
 -	sin(x) (sine wave)
 -	x^3 - 2*x^2 + 4 (cubic function)

2.	Set the domain:
- Enter the starting x-value in the "Start:" field
- Enter the ending x-value in the "End:" field
- Default values are -10 to 10

3.	Click the "Plot" button to generate the graph

**Function Syntax**
- Use standard mathematical notation
- Available operations:
- Basic arithmetic: +, -, *, /
- Powers: ^ or **
- Functions: sin, cos, tan, log, sqrt, abs, exp

**Example Functions**
- Linear: x
- Quadratic: x^2
- Cubic: x^3
- Sine wave: sin(x)
- Combined: x^2 + sin(x)
- Exponential: exp(x)
- Logarithmic: log(x) (requires x > 0)

## **Error Handling**

The application handles various errors gracefully:
- Invalid mathematical expressions: Shows "ERROR" in the calculator display
- Undefined operations (e.g., division by zero): Shows "ERROR" in the calculator display
- Invalid domain for graphing: Shows an error message
- Invalid function syntax: Shows an error message on the graph

## **Tips and Tricks**

1.	Use parentheses to group operations: (2+3)*4
2.	For negative numbers in functions, use parentheses: sin(-x) or sin((-1)*x)
3.	For inverse trigonometric functions, use the calculator to compute the angle
4.	Adjust the domain range for better visualization of specific function behaviors
5.	Use the DEL button to correct mistakes without clearing the entire expression

**Troubleshooting**

1.	Application doesn't start: 
- Ensure all required libraries are installed
- Check Python version compatibility
2.	ERROR displayed on calculator: 
- Verify mathematical expression syntax
- Check for operations outside their domains (e.g., √(-1))
3.	Graph doesn't display: 
- Verify function syntax
- Try a different domain range
- Check if function is undefined in the specified domain
4.	Slow graph rendering: 
- Try a smaller domain range
- Simplify the function if possible
- Restart the application if memory usage is high
5.	Incorrect calculation results: 
- Verify expression syntax and operator precedence
- Ensure trigonometric functions use the correct angle measure (degrees)
