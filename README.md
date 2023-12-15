# Problem.4
# Problem 4: Calories Burned

# Input first name and number of steps
first_name = input("Enter first name: ")
steps_walked = int(input("Enter number of steps walked: "))

# Calculate calories burned (0.25 calories per step)
calories_burned = steps_walked * 0.25

# Display results
print(f"\nFirst Name: {first_name}\nCalories Burned: {calories_burned}")
