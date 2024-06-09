## Prettier a formating tools for web developers

Prettier is an open source formater which improves productivity by formating codes in a organized manner for all the codebase of that project. It will autometicaly format codes on save the file.

## How to install Prettier

To install pretter run <code>npm install --save-dev pretter</code> in command line. this command will install pretter for your project as a dev dependency.

## How to run prettier

You can run pretter from command line (terminal) or useing prettier plugin in vscode. If you run <code>npx prettier "example.html" .write</code> it will format your code on that file.
You can also use prettier plugin to automate this process by ad this lines of code in <code>.vscode > settings.json file</code> file :

<code>{
"editor.defaultFormatter" : "esbenp.prettier-vscode", "editor.formatOnSave" : true
}</code>

## Prettier use cases

Prettier can format languages of code which boot in productivity. the languages that prettier can forma like <code>HTML, CSS, Javascript, Typescript, Sass, Less, JSX, TSX, Markdown, Yml</code> etc.
