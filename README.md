Name : PHANI PAGIDIMARRI

Company : CODTECH IT SOLUTIONS

ID : CT08DS55

Domain : C Prograaming

Duration : Dec to Jan 2025

Mentor : Neela Santhosh

# OverView Of the Project

## Project: Temperature Converter Using C 

## Objective 
The aim of this Project is to convert temperatures between Celsius, Fahrenheit and Kelvin. This Program allows the user to input a temperature in one scale and output the converted temperature in another scale. 

## Key Activities
### 1. Input Handling:

The program accepts user input (temperature values and menu choices) and validates it for correctness.
Error handling for invalid inputs ensures the program operates robustly.


### 2. Menu-Driven Interaction:

A simple text-based interface allows the user to select options for conversions or exit the program.
Loops and conditions control the flow of the menu and repeat tasks as needed.


### 3.Temperature Conversion:

Mathematical computations are performed based on standard formulas:
        Celsius to Fahrenheit : F= (C *9/5)+32
        Fahrenheit to Celsius : C= (F-32)*5/9
        
 
### 4.Modularity:

The program uses functions (celsiusToFahrenheit and fahrenheitToCelsius) to separate temperature conversion logic from the main workflow.
Improves code readability and reusability.


### 5.Control Flow:

do-while loop ensures the program runs repeatedly until the user decides to exit.
switch-case structure handles user choices for better clarity.


### 6.Output Formatting:

Provides formatted and user-friendly output for the converted values.

## Technologies Used 

### C :
Primary and General purpose coding language close-to-hardware
### Math Logic : 
Simple arithmetic operations to perform conversions based on mathematical formulas.
### Integrated Development Environment (IDE) :
Typically written and executed in environments like:
Visual Studio (using scanf_s).
### Basic Error Handling :
Ensures invalid inputs are gracefully handled using validation loops.
### CLI-Based User Interaction:
The program operates in a console or terminal, leveraging text-based input and output.

## Explanation 

# Function Prototypes
float celsiusToFahrenheit(float celsius);
float fahrenheitToCelsius(float fahrenheit);
These declare the functions used to convert temperatures. They are defined at the end of the program.
The # Main Function displays with three options and prompts based on the user choice.
To Convert the temperature between Celsius and Fahrenheit , program uses Math logic and the formula is : 

        Celsius to Fahrenheit : F= (C *9/5)+32
        Fahrenheit to Celsius : C= (F-32)*5/9
        
By using the # Choice handling, If user Selects Celsius to Fahrenheit option then based on the user input of Celsius data,  it converts the temperature from Celcius to Fahrenheit. Else user selects Fahrenheit to Celsius option then based on the user input , it converts the tempertature from Fahrenheit to Celcius. 

In case , if user want to convert many temperatures from Celcius to Fahrenheit or Fahrenheit to Celsius then, after each conversion , simply by clicking "Y" or "y" user can continue. Else user can click on "N" or "n" or can select number "3" to stop conversion/exit the program. This everything is done by # choice handling.
