# My VS CODE SETTINGS

## Themes

### Ayu

A simple theme with bright colors and comes in three versions — dark, light and mirage for all day long comfortable work.

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install ayu`

Then Set File Icon Theme as Ayu

[Website](https://github.com/dempfi/ayu)

## Plugins

### Bracket Pair Colorizer

A VS Code extension that gives you a simple command to quickly toggle the global “Bracket Pair Colorization” setting added in VS Code v1.60.

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install 'Bracket Pair Colorization'`

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

### Prettier ESLint

Code formatter using prettier

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

`ext install rvest.vs-code-prettier-eslint`

[Website](https://marketplace.visualstudio.com/items?itemName=rvest.vs-code-prettier-eslint)

## Personal settings

```

{
	"editor.fontSize": 16,
	"editor.lineHeight": 24,
	"editor.fontFamily": "Fira Code",
	"editor.fontLigatures": true,
	"editor.rulers": [80, 120],
	"editor.formatOnSave": true,
	"editor.renderLineHighlight": "gutter",
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"editor.quickSuggestions": {
		"other": true,
		"comments": false,
		"strings": true
	},
	"editor.codeActionsOnSave": {
		// For ESLint
		"source.fixAll.eslint": true
	},
	"prettier.useTabs": true,
	"terminal.integrated.defaultProfile.linux": "zsh",
	"terminal.integrated.fontSize": 14,
	"explorer.compactFolders": false,
	"[html]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"workbench.colorTheme": "Ayu Dark",
	"workbench.iconTheme": "ayu",
	"editor.bracketPairColorization.enabled": true
}

```
