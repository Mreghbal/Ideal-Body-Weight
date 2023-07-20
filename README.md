# Ideal Body Weight Calculator

This is a Python code that calculates the Ideal Body Weight (IBW) based on height and gender. The code provides a function `calculate_ibw` that takes the height centimeters and the gender ('male' or 'female') as input and returns the calculated Ideal Body Weight in kilograms.

## Table of Contents
- [Introduction](#roduction)
- [Usage](#usage)
- [How to Run](#how-to-run)
- [Understanding the Code](#understanding-the-code)
- [Limitations](#limitations)
- [Contact](#contact)

## Introduction
The Ideal Body Weight (IBW) is a measure used to estimate a person's healthy weight range based on their height and gender. It is commonly used in healthcare settings to assess an individual's weight status and determine appropriate treatment plans.

The formula used to calculate the IBW varies for males and females. For males, the formula is 50 + 0.91 * (height - 152.4), and for females, it is 45.5 + 0.91 * (height - 152.4). These formulas are based empirical data and provide a rough estimate of the ideal weight for a given height and gender.

## Usage
To use this code, follow the steps below:

1. Install Python: Make sure you have Python installed on your system. You can download it from the official Python website: [python.org](httpswww.python.org/).

2. Clone the Repository: Clone this GitHub repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/ideal-body-weight-calculator.git
   ```

3. Navigate to the Project Directory: Open a terminal/command prompt and navigate to the directory where you cloned the repository.

4. Run the Code: Execute the following command to run the code:
   ```
   python calculate_ibw.py
   ```

5. Enter Input Values: When prompted, enter the height in centimeters and the gender ('male' or 'female').

6. View the Result: The code will calculate the Ideal Body Weight based on the provided input and display it on the console.

## How to Run
To run the code, you need to have Python installed on your system. Follow the steps below to execute the code:

1. Open a terminal/command prompt.

2. Navigate to the directory where you cloned the repository using the `cd` command.

3. Run the code executing the following command:
   ```
   python calculatew.py
   ```

4. Follow the instructions on the console and provide the required input values (height and gender).

5. The calculated Ideal Body Weight will be displayed as output on the console.

## Understanding the Code
 code consists of a single function `calculate_ibw` that takes two arguments: `height` and `gender`. It uses an if-else statement to determine the appropriate formula based on the gender provided.

For males, the formula is `50 + 0.91 * (height - .4)`, and for females, it is `45.5 + 0.91 * (height - 152.4)`. The height should be provided in centimeters a float value.

If an invalid gender is provided, a `ValueError` is raised with an error message indicating that only 'male' or 'female' are accepted values.

The calculated Ideal Body Weight is then returned as the output of the function.

## Limitations
It's important to note that the Ideal Body Weight calculated using this code an estimate based on height and gender. It does not take into account other factors such as body composition, muscle mass, and individual variations. Therefore, it should be used as a general guideline and not as a definitive measure of an individual's ideal weight.

For personalized advice on weight management and health, it is recommended to consult with a healthcare professional or a registered dietitian.

## Contact
If you have any questions or suggestions regarding this code, feel free to reach out to me on LinkedIn or Twitter:

LinkedIn: [Reza Eghbal](https://www.linkedin.com/in/mreghbal)

Twitter: [Reza Eghbal](https://twitter.com/mreghbal)

Thank you for using the Ideal Body Weight Calculator!
