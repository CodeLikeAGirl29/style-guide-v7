# Style Guide

In this project, we've provided completed index.html and styles.css files. You will be responsible for converting the CSS into Sass by splitting the code into several Sass partial files. You will also look for repeated values (length units, colors, etc.) throughout the CSS and store them in Sass variables. After completing the project, you'll have a useful Sass micro-framework to quickly prototype other websites.

## Built with:

![sass](https://camo.githubusercontent.com/7436ecde5696a856dd865d3fc81fa2612054f468e12fdb5d591e7a19a46fc9f7/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d5361737326636f6c6f723d434336363939266c6f676f3d53617373266c6f676f436f6c6f723d464646464646266c6162656c3d)

## Main Color Reference

| Color         | Hex                                                              |
| ------------- | ---------------------------------------------------------------- |
| Turquoise     | ![#58e1c1](https://via.placeholder.com/10/58e1c1?text=+) #58e1c1 |
| Sky Blue      | ![#51ddfc](https://via.placeholder.com/10/51ddfc?text=+) #51ddfc |
| Purple        | ![#927bc1](https://via.placeholder.com/10/927bc1?text=+) #927bc1 |
| Coral         | ![#fd7856](https://via.placeholder.com/10/fd7856?text=+) #fd7856 |
| Pastel Indigo | ![#deb2ee](https://via.placeholder.com/10/deb2ee?text=+) #deb2ee |

## Screenshots

![App Screenshot](https://res.cloudinary.com/codelikeagirl29/image/upload/v1680393286/projects/Circles-UI-Kit_kbmdqg.png)

## Resources

- [Install Sass](https://sass-lang.com/install)
- [Scout app](https://scout-app.io/)
- [Using Scout](https://towardsdev.com/sass-and-scout-app-415f41811975)
- [Team Treehouse project](https://teamtreehouse.com/projects/web-style-guide#getting-started)

---

## Instructions Guide
1. Structure your folders.
    - Start by creating a scss folder inside your project's root folder. All of your Sass files, including sub-folders to organize them, will go in here.
    - Create sub-folders inside of the scss folder for your base, component, and utilities partials.
    - Create a css folder inside of the project's root folder. This is where your output css will be generated.
2. Create the file structure.
    - Change the normalize.css file into a Sass partial and save it to the base folder.
    - Create a typography partial and save it to the base folder.
    - Create at least 4 different component partials that group together the major sections of the site. For example: navigation, grid, form, and button partials.
    - Inside the utilities folder, create variables and mixins partials.
    - In each of your scss sub-folders, create an _index.scss file. These files will be used to import individual partials from each sub-folder.
    - Create a styles.scss. Use this file to import all of the _index.scss files from your sub-folders.
3. Setup Sass to watch for changes.
    - From the terminal, navigate to your project's root folder.
    - Run the command sass --watch scss:css so that Sass will continuously update your output CSS as you make changes to your Sass.
4. Create your variables.
    - Looking through the resources/css/styles.css file, identify common colors and sizes that can be converted to variables.
    - Create at least 5 color variables.
    - Create a variable that stores the size of the media query breakpoint.
5. Add styles to the typography partial.
    - Scan the resources/css/styles.css file for styles related to font family, size, and weight.
    - Pay particular attention to those that are targeting tag names like a, h1, body, or the universal selector *.
    - Add these styles into the typography partial.
6. Move styles into components.
    - Transfer the remaining CSS into their respective components. For example, any class selectors that begin with grid, column, or rows could go in the grid component.
    - Be sure to update any styles that use color values with the Sass variables you created in the previous step.
7. Check your work
    - Double-check all of your work, click on the "How you will be graded" tab above and compare your project to the rubrics listed there. Post your project in the #review-my-project channel so that the rest of the community can see your awesome project and give feedback before submitting it.
### Extra Credit
To get an "exceeds" rating, complete all of the steps below:

1. Use a nested selector structure for at least one component.
    - Create a base selector for a group of related styles.
    - Inside of that selector, use the Sass parent selector: & to append a child class selector to the base. An example would be in the navigation component use .nav as the base selector, and nest .nav-link inside of it.
2. Use built in Sass function to add hover effect.
    - Created a hover effect for buttons.
    - For the effect, lighten the button's background color by 15%.
    - Add a CSS transition so that the color change fades in.
> NOTE: Getting an "Exceed Expectations" grade.
> See the rubric in the "How You'll Be Graded" tab above for details on what you need to receive an "Exceed Expectations" grade. 
