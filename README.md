# Meal Planner Project

## Overview
This Meal Planner project is designed to assist users in organizing their meal plans, recipes, and recipe collections efficiently. It includes three main classes: `Recipe`, `MealPlan`, and `RecipeBook`.

## Classes

### Recipe
- **Purpose:** Represents a single recipe with details such as ingredients and instructions.
- **Attributes:**
  - `name` (string): The name of the recipe.
  - `ingredients` (list): A list of ingredients required for the recipe.
  - `instructions` (string): Step-by-step instructions on how to prepare the dish.

### MealPlan
- **Purpose:** Represents a meal plan consisting of multiple recipes scheduled for a certain period.
- **Attributes:**
  - `name` (string): The name of the meal plan (e.g., "Weekly Dinner Plan").
  - `recipes` (list): A list of `Recipe` objects planned for the week.
  - `date` (string): The start date for the meal plan.

### RecipeBook
- **Purpose:** Serves as a collection of recipes that can be added to a meal plan.
- **Attributes:**
  - `recipes` (list): A list of all `Recipe` objects in the recipe book.

## Usage
1. To create a new recipe, instantiate the `Recipe` class with the recipe name, ingredients, and instructions.
2. Add recipes to your `RecipeBook` using the appropriate methods.
3. Create a `MealPlan` by selecting recipes from your `RecipeBook` and scheduling them for specific days.

## Installation
Clone the repository and include it in your project to utilize the Meal Planner functionalities.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Developed by kimoo12343.
- Thank you to all contributors and supporters.