# HTML CSS Layouts

## Conditions

1. All layouts should be done with pure vanilla css and html
2. No frontend frameworks or third party libraries for css are allowed ( like sass, astro, react, vue, bootstrap)
3. Plain javascript is allowed but it should not to used for adding, removing html elements that affect the layout. It can however be used for adding content (text), date and time
4. All three files (html, css, javascript) should have the name `index` i.e. `index.html`, `index.css` and `index.js`
5. All three files should be located in the root folder of the project and not in any nested folders like `styles` or `scripts`  
6. All layouts need to be fully responsive both for desktop and mobile screens
7. Any images, fonts, icons used should be located in a folder name assets
8. Links to any external sources like CDNs, Fonts like google fonts, fontawesome are not allowed
9. All styles must be located in index.css only
10. Inline styles are not allowed
11. All javascript code needs to located in `index.js` only

## Recommendations

1. Use semantic html elements e.g. `<nav>`, `<footer>`, `<header>`
2. Use classes with meaningful & descriptive names
3. Avoid unnecessary nesting of elements
4. the lesser number of style rules used to achieve the goal, the better
5. Use css variables whener a value is repeated

## Project Structure

```bash
project_name
|_ index.html
|_ index.css
|_ index.js (optional)
|_ assets (optional)
|_ README.md (optional)
|_ .git/ (optional)
|_ .gitignore (optional)
```
