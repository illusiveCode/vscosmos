# VS Code Settings
### All things vscode, my preferences, settings, themes etc.
# Font

* [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

## Themes/Color

* [Catppuccin Icons](https://marketplace.visualstudio.com/items/?itemName=Catppuccin.catppuccin-vsc-icons)
    * Soothing pastel icon theme

## Extensions

* Theme / Editor Experience
  * [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
    * Change the font size with keyboard shortcuts.
  * [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    * Integrates ESLint JS
  * [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    * Automatically format javascript, JSON, CSS, Sass
  * [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
    * Auto generate TypeScript (and other languages) types from JSON data., and HTML files.
  * [PostCSS Intellisense and Highlighting](https://marketplace.visualstudio.com/items?itemName=vunguyentuan.vscode-postcss)
    * Works better than the other more popular one of a similar name.
  * [Pretty TypeScript Errors](https://marketplace.visualstudio.com/items?itemName=yoavbls.pretty-ts-errors)
    * Makes TS errors more human readable.
  * [Jest](https://marketplace.visualstudio.com/items/?itemName=Orta.vscode-jest)
    * Unit testing library
  * [Jest Runner](https://marketplace.visualstudio.com/items/?itemName=firsttris.vscode-jest-runner)
    * Simple way to run or debug a single (or multiple) tests from context-menu  
* Useful Tools
  * [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
    * Auto generate TypeScript (and other languages) types from JSON data.
  * [Code Snap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)
    * Take pictures of code with your VS Code Theme / Font settings.
  * [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)
    * Make HTTP requests from inside VS Code (similar to Postman / Insomnia).
* Languages and Libraries
  * [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)
    * XML Formatting, XQuery, and XPath Tools for Visual Studio Code.
  * [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
    * Intelligent Tailwind CSS tooling for VS Code.
  * React
    * [ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
      * Extensions for React, React-Native and Redux in JS/TS with ES7+ syntax. Customizable. Built-in integration with prettier.
    * [CSS to JSS](https://marketplace.visualstudio.com/items?itemName=infarkt.css-to-jss)
      * Convert CSS to JSS
    * [CSS in JS](https://marketplace.visualstudio.com/items?itemName=paulmolluzzo.convert-css-in-js)
      * Get syntax highlighting when working with CSS in JS template strings.
    * [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components)
      * Syntax highlighting for styled-components.

### Extension package names for easy install

```
catppuccin.catppuccin-vsc
catppuccin.catppuccin-vsc-icons
fosshaas.fontsize-shortcuts
dbaeumer.vscode-eslint
esbenp.prettier-vscode
quicktype.quicktype
orta.vscode-jest
firsttris.vscode-jest-runner
vunguyentuan.vscode-postcss
yoavbls.pretty-ts-errors
quicktype.quicktype
adpyke.codesnap
rangav.vscode-thunder-client
DotJoshJohnson.xml
bradlc.vscode-tailwindcss
dsznajder.es7-react-js-snippets
infarkt.css-to-jss
paulmolluzzo.convert-css-in-js
styled-components.vscode-styled-components
```

# Settings

```json
{
  "editor.inlineSuggest.enabled": false,
  "editor.lineHeight": 0,
  "editor.linkedEditing": true,
  "editor.minimap.enabled": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "editor.detectIndentation": true,
  "editor.fontFamily": "Anonymous Pro",
  "editor.fontLigatures": true,
  "editor.fontSize": 13,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorStyle": "line",
  "editor.cursorBlinking": "phase",
  "terminal.integrated.fontSize": 13,
  "editor.accessibilitySupport": "off",
  "workbench.sideBar.location": "right",
  "workbench.iconTheme": "catppuccin-mocha",
  "workbench.colorTheme": "Catppuccin Mocha",
  "workbench.layoutControl.enabled": false,
  "workbench.navigationControl.enabled": false,
  "window.commandCenter": false,

  // git
  "git.autofetch": true,

  // eslint
  "eslint.enable": true,
  "eslint.validate": ["react", "typescript", "html", "javascript"]
}
```

