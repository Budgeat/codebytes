### Instructions
- As part of this exercise you will be building a mobile app that tests your knowledge of both front-end and back-end concepts
- Please start by creating a fork of the repo so you can push your changes to it
- Complete all the tasks as described by their requirements
- You have freedom over what technologies to use, but the preferred ones are:
    - PHP/Laravel
    - Dart/Flutter
- Don’t spend more than 4-6 hours on this

### Evaluation Criteria
- Software development best practices
- Completeness: did you build all required features? Are all the tests running successfully?
- Correctness: does the app function in sensible ways and provide good UX?
- Maintainability: is the code clean, maintainable, and easy to follow with sufficient documentation?
- Show your progress through your commit history, don’t wait until you’re code complete to push your code.

######
# Tasks
######

## Task #1 - Starting with a data model.
- Design the database schema for the recipe data present in the project folder (pay close attention to the data and build the optimal structure):
    - recipes.csv
    - recipe_ingredients.csv
- Insert the data into your database for later use

## Task #2 - Let’s see the recipes…
- Build a mobile app that displays the recipes you just created
- The app should have a home screen that displays the main recipe data (title, price, servings, etc.)
- When clicking on a recipe, it should navigate to another screen that shows the recipe details, in this case the ingredients for that recipe
- You have creative freedom on how the app looks but be sensible about design choices
- Use MVC pattern for your solution

## Task #3 - Recipes are missing instructions!
- We forgot to include the instructions in our sample data, but don’t worry, you can get the instructions from the following API endpoint: https://admin.mybudgeat.com/codebytes/get-recipe-instructions
- A single call will give you the instructions for all recipes
- Display the instructions alongside the ingredients so it’s all in one place

######
# All done!
######

### Submitting the code
Please organize, design, test and document your code as if it were going into production. Once complete, push your final commit to your own developer branch and let us know that you have completed the assignment along with your fork url and branch name. Make sure your repo is public so we can access it and please don’t make any changes to the code after you’ve submitted it. If you have issues forking and pushing to your forked repository, please just send us a compressed folder with all your files.

All the best and happy coding,

The Budgeat Team
