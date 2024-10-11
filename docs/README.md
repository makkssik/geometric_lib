# Project Documentation

## General Description of the Solution

This project is a program for calculating the area and perimeter of geometric figures: circles and squares. The user inputs the name of the figure, selects a function (area or perimeter), and specifies the necessary dimensions. The program performs the calculation and outputs the result. The main mathematical formulas for the calculations are included in the documentation.

## How to Use the Calculator:
1. Run `python calculate.py`
2. Enter the figure name. Available are Circle, Square.
3. Enter the function: Area or Perimeter.
4. Enter figure sizes. Radius for circle, one side for square.
5. Get the answer!

## Math Formulas

### Area
- Circle: `S = πR²`
- Square: `S = a²`

### Perimeter
- Circle: `P = 2πR`
- Square: `P = 4a`

## Function Descriptions

### `calc(fig, func, size)`

This function performs the calculation based on the provided parameters.

#### Parameters:
- `fig` (str): The name of the figure (available options are 'circle' and 'square').
- `func` (str): The calculation to perform (available options are 'perimeter' and 'area').
- `size` (list): A list of dimensions required for the calculation.

#### Example Calls:
```python
calc('circle', 'area', [5])  # Calculates the area of a circle with a radius of 5
calc('square', 'perimeter', [4])  # Calculates the perimeter of a square with a side length of 4