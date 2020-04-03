This is a proof of concept for generating an html file from a handlebars template.

The template files can be found in the `/src` folder.  This contains several `*.handlebars` files:
*  The primary `index.handlebars` template
* Three reference templates in the `/src/partials` folder:
  * `dots.handlebars`
  * `gt.handlebars`
  * `worker.handlebars`.

To generate a `.html` sheet from these templates, perform the following steps:

1. Install [Node.js with npm](https://nodejs.org/) (choose the "LTS" version)
2. Open a command prompt scoped to the /handlebars-poc folder
3. Run command `npm install` in the command prompt.
4. Run command `npm run generate` in the command prompt.

Expected result: `simple-sheet.html` is generated in this folder.

(Steps 1 through 3 only have to be done once. Step 4 can be repeated after modifying the `.handlebars` template files.)
