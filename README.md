# Miles-per-gallon-calculator-in-python
#program name
#your name
#date.

# This is a Miles-per-Gallon calculator

#greet the user
print('Greetings!!')
# Prompt the user for miles driven and gallons of gas used
Milesdriven = float(input("Enter the number of miles driven: "))
Gallonsgasused = float(input("Enter the number of gallons of gas used: "))

# Calculate the miles per gallon (mpg)
MPG = round (Milesdriven / Gallonsgasused, 2)

# Display the result
print("The miles per gallon (MPG) for the car is:", MPG)
