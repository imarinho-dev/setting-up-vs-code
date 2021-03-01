# My VS CODE SETTINGS

## Themes

### Dracula Official

Official Dracula Theme. A dark theme for many editors, shells, and more.

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install dracula-theme.theme-dracula`

[Website](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)

### Material Icon Theme

Material Design Icons for Visual Studio Code

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install PKief.material-icon-theme`

[Website](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

## Plugins

### Babel JavaScript

VSCode syntax highlighting for today's JavaScript

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install mgmcdermott.vscode-language-babel`

[Website](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel)

### Bracket Pair Colorizer

A customizable extension for colorizing matching brackets

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install CoenraadS.bracket-pair-colorizer`

[Website](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

### Code Runner

Run C, C++, Java, JS, PHP, Python, Perl, Ruby, Go, Lua, Groovy, PowerShell, CMD, BASH, F#, C#, VBScript, TypeScript, CoffeeScript, Scala, Swift, Julia, Crystal, OCaml, R, AppleScript, Elixir, VB.NET, Clojure, Haxe, Obj-C, Rust, Racket, Scheme, AutoHotkey, AutoIt, Kotlin, Dart, Pascal, Haskell, Nim,

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install formulahendry.code-runner`

[Website](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

### Color Highlight

Highlight web colors in your editor

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install naumovs.color-highlight`

[Website](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

### DotENV

Support for dotenv file syntax

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install mikestead.dotenv`

[Website](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

### EditorConfig for VS Code

EditorConfig Support for Visual Studio Code

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install EditorConfig.EditorConfig`

[Website](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

### ES7 React/Redux/GraphQL/React-Native snippets

Simple extensions for React, Redux and Graphql in JS/TS with ES7 syntax

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install dsznajder.es7-react-js-snippets`

[Website](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)

### ESLint

Integrates ESLint JavaScript into VS Code.

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install dbaeumer.vscode-eslint`

[Website](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

### Markdown All in One

All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install yzhang.markdown-all-in-one`

[Website](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

### Live Server

Launch a development local Server with live reload feature for static & dynamic pages

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install ritwickdey.LiveServer`

[Website](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

### Live Share

Real-time collaborative development from the comfort of your favorite tools.

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install MS-vsliveshare.vsliveshare`

[Website](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)

### Prettier - Code formatter

Code formatter using prettier

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install esbenp.prettier-vscode`

[Website](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## Personal settings

```

{
	"workbench.colorTheme": "Dracula",
	"workbench.iconTheme": "material-icon-theme",
	"editor.fontSize": 16,
	"editor.lineHeight": 24,
	"editor.fontFamily": "Fira Code",
	"editor.fontLigatures": true,
	"editor.rulers": [80, 120],
	"editor.formatOnSave": true,
	"terminal.integrated.shell.osx": "/bin/zsh",
	"terminal.integrated.fontSize": 14,
	"editor.renderLineHighlight": "gutter",
	"editor.quickSuggestions": {
		"other": true,
		"comments": false,
		"strings": true
	},
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"[html]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[rust]": {
		"editor.defaultFormatter": "rust-lang.rust",
		"editor.formatOnPaste": true,
		"editor.formatOnSave": true
	},

	"editor.codeActionsOnSave": {
		// For ESLint
		"source.fixAll.eslint": true
	},
	"emmet.includeLanguages": {
		"javascript": "javascriptreact"
	},

	"prettier.packageManager": "yarn",
	"prettier.jsxSingleQuote": true,
	"prettier.singleQuote": true,
	"prettier.useTabs": true,
	"javascript.updateImportsOnFileMove.enabled": "always",
	"explorer.compactFolders": false
}

```
