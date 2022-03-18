__Portfolio In Terminal Style

This is a SPA in reactJS with a MacOS terminal style.
The terminal is a draggable and resizable React component and has sections about me, so it will be my personal portfolio for while.

__How to setup:

To use this page, first fork this repository and clone it on your machine, so you  can add your information.

To edit the sections and put your informations you should edit the contentEN object in the src/text/ path.
Besides, you can add more sections creating more properties to the object.

Or if you want to add support to another language you should create an object like these in the mentioned path and import it in the src/text/textManager.js file.

Read the files of the src/text/ path and you'll understand more about how to edit, add more sections, or support for multiples languages.

If something isn't clear feels free to open an issue.

__Deploy :

After making your changes, you can deploy the app on github pages. The steps are:

Install github pages as dev dependecies:

npm install gh-pages --save-dev

Put the link of your homepage in the homepage properties of package.json, the link is like this http://{username}.github.io/{repo-name}.

After all, run the command:

npm run deploy

And the application will be deployed in the homepage link.
