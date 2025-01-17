# Building-a-Calorie-Intake-Calculator

Enhance the Diet Coach app by creating the nutritional_summary() function to calculate and return the total nutritional values from the nutrition_dict dataset.

Function Output:

If all the foods are present in the dataset, the function returns a dictionary with keys: "calories", "total_fat", "protein", "carbohydrate", "sugars".

If any food is missing from the dataset, the function returns the name of the first missing item.

Input Format:

Dictionary: For example, calling nutritional_summary({"Croissants, cheese": 150, "Orange juice, raw": 250}) should output {'calories': 733.5, 'total_fat': 32.0, 'protein': 15.55, 'carbohydrate': 96.5, 'sugars': 38.025} Here, 150 and 250 represent the grams of each food.

Handling non-existent keys: For example, calling nutritional_summary({"Croissant": 150, "Orange juice": 250}) should output "Croissant".