# Ideal-Body-Weight
Python code that calculates the Ideal Body Weight (IBW) in actual condition.
In this code, the calculate_ibw function takes two arguments: height and gender. It uses different formulas based on gender to calculate the Ideal Body Weight (IBW). For males, the formula is 50 + 0.91 * (height - 152.4) and for females, it is 45.5 + 0.91 * (height - 152.4).

The height should be provided in centimeters as a float value, and the gender should be specified as either 'male' or 'female'. If an invalid gender is provided, a ValueError will be raised.

In the example usage section, I've provided a sample value for height_cm and set the gender to 'male'. The calculate_ibw function is called with these values, and the calculated Ideal Body Weight is then printed as output.

Please note that this formula provides an estimate of the Ideal Body Weight based on height and gender, and there are various other factors to consider when determining an individual's ideal body weight. Consultation with a healthcare professional is recommended for personalized advice.
