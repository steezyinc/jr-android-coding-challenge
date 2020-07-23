# Junior Android Coding Challenge
## Context
You have been tasked to create an app that does the following: display recipes, allow users to favorite recipes, and also display the ingredients and description of a recipe when clicked on.

## Product Requirements
As a user:
- [ ] I want to be able to change between two tabs
  - [ ] I want the title of one tab to be "All Recipes"
  - [ ] I want the title of one tab to be "Favorite Recipes"
  
- [ ] I want to be able to see a list of all recipes in one tab
- [ ] I want to be able to see a list of favorite recipes another tab
  - [ ] I want to see "No Favorite Recipes" if there are no recipes currently favorited 
  
- [ ] I want to be able to favorite/un-favorite different recipes from the "All Recipes Tab"
    - [ ] I want to be able to un-favorite recipes from the "Favorite Recipes Tab"
    - [ ] I want the list shown to be current when switching between tabs
  
- [ ] I want to be able to click anywhere on a recipe name and display a new page for that specific recipe
  - [ ] I want to be able to see a list of ingredients for this recipe
  - [ ] I want to be able to see a description of this recipe
  - [ ] I want to be able to favorite/un-favorite this specific recipe
  - [ ] I want to be able to click on a button to close this page and return back to the list of recipes
  
- [ ] I want to be able to see that state changes are handled across device rotations

### UI Requirements
- Margins on either side of a list item should be 16dp
- Margins in between list items should be 8dp
- Margins on either side for the recipe description should be 16dp
- Text size for Recipe Name on the `Recipe Specific Page` should be 30sp
    - Margins on either side of text should be 5dp
 
## Your Goal
Create a simple app that satisfies the product requirements. 

While the list of recipes given back in the json response is finite, assume that any lists are dynamic enough to handle any amount of recipes.

Put comments where appropriate in order to show thought process.  Please consult the wireframes on how the app should look.

- [All Recipes](./app/src/wireframes/all_recipes.png)
- [Favorite Recipes](./app/src/wireframes/favorite_recipes.png)
- [No Favorite Recipes](./app/src/wireframes/no_favorite_recipes.png)
- [Recipe Specific Page](./app/src/wireframes/recipe_specific_page.png)

`recipes.json` has been provided for you  in the `/assets` folder to read and pull the necessary data from to display within the app.  The project has been set up with an initial method `getJson()` to read the json file and turn it into a `JSONObject`. How you use this `JSONObject` to complete the task is up to you. `empty_star.xml` and `filled_star.xml` will be provided as drawables in the project in order for you to use.  For the "X" on the recipe screen, you can use @android:drawable/ic_delete.

You are free to use any open source libraries that you deem fit to accomplish this task. However, try to keep it as simple as possible. If you need to use any android specific libraries, please use the `androidx` library where applicable.  The minimum API of this project will be 24. This project must be completed in Java.

## Instructions
- Clone this repository and import your project into Android Studio. Cloning can be done either from Github GUI or Android Studio itself.
- Build a performant, clean and well-structured solution.
- Commit early and as often as possible!
- When you're finished please export a ZIP of the project using Android Studio `File -> Export to Zip File` and send us an email with the attachment to notify us.

Best of luck and happy coding!

## Assumptions
List out any assumptions you made while working on the project.
