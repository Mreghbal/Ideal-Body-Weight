def calculate_ibw(height, gender):
    """
    Calculate Ideal Body Weight (IBW).

    Arguments:
    height -- The height in centimeters (float).
    gender -- The gender ('male' or 'female').

    Returns:
    ibw -- The calculated Ideal Body Weight in kilograms (float).
    """

    if gender.lower() == 'male':
        ibw = 50 + 0.91 * (height - 152.4)
    elif gender.lower() == 'female':
        ibw = 45.5 + 0.91 * (height - 152.4)
    else:
        raise ValueError("Invalid gender. Please provide 'male' or 'female'.")

    return ibw

# Example usage
height_cm = 170
gender = 'male'

ibw_result = calculate_ibw(height_cm, gender)
print("Ideal Body Weight:", ibw_result, "kg")
