### Creating a Gatsby Web App

Followed Gatsby [quick start](https://www.gatsbyjs.com/docs/quick-start/) instructions.

**Important note:** When creating a new Gatsby site, make sure to use the 'Hello World' git repo. It will pull the files needed to build the starter app.
Not your Github repo lol.

### Adding TailwindCSS

Used a combination of these tutorials: [TailwindCSS in under 5 minutes](https://hashinteractive.com/blog/tailwind-css-and-gatsby-in-under-5-minutes/) 
and [VSCode + Stylelint + Tailwind CSS = ♥️](https://andrich.me/vscode-stylelint-tailwind-css-are-love). I used this snippet of code to purse unused CSS classes 
in the tailwind.config.js file (located in root directory).

`  purge: ["./src/**/*.js"],
   target: "relaxed",`
