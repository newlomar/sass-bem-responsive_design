Saas
  - Syntactically Awesome Style Sheets
  - CSS pre-processor

Sass Partials
- Instead to havint to look through one giant long css file, you can split up your styles into multiple files and even keep them more organized with subfolders.
- This allow you to keep different parts of the website separated in different files and it makes easier to locate styles when you are debugging a website.
- Having your styles separated into differents files will allow multiple developers to work on the code base at the same time, with a lower chance of more than one developer working on the same file at the same time, which decreases the chances of having a code conflict in your version control.

Sass/CSS variables
- Variables are ways that you can store bits of information with and then give them a label with a name. Usually, you select a descriptive name so it lets you understand what kind of information is being stored in that variable.
- Right now, both scss and css have variables. In css they are called css custom properties
- Using variables in styles makes easier if we need to change the styles of color, spacing, etc..
- When you need to use the same value in multiple places, you refer to the variable instead of the value. So, if you need to change it, you will change only in one place.
- It's also easier to remember the name of variable instead of the property, in case of colors, the hex or hsl or rgb values.