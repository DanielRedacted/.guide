# Usage Guide

## Writing a `.guide` File

A `.guide` file is a plain text file that you can easily write in any text editor. Here's an example format for a recipe:

Title: Simple Pancake Recipe Author: Jane Doe Servings: 4 Time: 10 minutes prep, 15 minutes cook

Tools:

Mixing bowl
Whisk
Non-stick skillet
Measuring cups
Measuring spoons
Ingredients: Dry Ingredients:

2 cups flour [Note: Use all-purpose flour] [Image: https://example.com/flour.jpg]
2 tablespoons sugar
2 teaspoons baking powder
1/2 teaspoon salt
Wet Ingredients:

2 eggs
1 1/2 cups milk
2 tablespoons melted butter [Note: Allow to cool before adding]
Instructions: Step 1: Prepare the Batter

Whisk together dry ingredients.
Beat eggs, add milk and butter.
Mix wet and dry ingredients.
Step 2: Cook Pancakes 4. Heat the skillet. 5. Pour batter, cook, flip. 6. Serve with toppings.

Notes:

Substitute milk with plant-based options.
perl
Copy code

You can write your own `.guide` files following this format.

## Using the HTML Interface

1. Navigate to `src/interface/index.html`.
2. Upload your `.guide` file or manually input your recipe.
3. The interface will parse and display the result.

## Running the Parser with Node.js

To run the parser programmatically, you can use the following command:

```bash
node src/index.js your_file.guide
yaml
Copy code

---