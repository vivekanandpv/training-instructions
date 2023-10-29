# React/Angular/Vue Training - Lab Setup

Please follow the instruction to install the software, setup the environment, and configure the editor


## Installation

 - Install Node.js: [from here](https://nodejs.org/en/download/current) or from your organization's software center
 - Install Angular CLI: `npm i -g @angular/cli` *(only for Angular training)*
 - Install Visual Studio Code: [from here](https://code.visualstudio.com/download) or from your organization's software center

## Version Check (in PowerShell)

 - `node --version`  # Should be >= v18
 - `npm --version` # Should be >= v8
### Angular Specific PowerShell Configuration
Please run the command: `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`
Select *All*

Check the Angular CLI version `ng version` # Should be >= v15

## VS Code Extensions to be installed:

 - Prettier
 - Code Spell Checker
 - Material Icon Theme
 - Simple React Snippets *(for React training)*
 - Angular Language Service *(for Angular training)*
 - Vue Language Features (Volar) *(for Vue training)*
 - TypeScript Vue Plugin (Volar) *(for Vue training)*

## VS Code Configuration:

 - Preferences > Settings > Search for *Format On*
	 - Check on
		 - Format on Paste
		 - Format on Save
		 - Format on Type
 - *Only for React training*
	 -  Preferences > Settings > Search for *jsx*
		 - Check on *Prettier: Jsx Single Quote*

## Starter Applications

 - For Angular: [get here](https://github.com/vivekanandpv/angular-training-starter)
	 - download, extract, open the inner directory (which has src, package.json) in VS Code
	 - In the integrated terminal, run the command: `npm i`
	 - Run the app with the command: `ng s --open`
	 - Your browser should now open a tab with http://localhost:4200 where you see the *Angular Training App*
 - For React: [get here](https://github.com/vivekanandpv/react-training-starter)
	 - download, extract, open the inner directory (which has src, package.json) in VS Code
	 - In the integrated terminal, run the command: `npm i`
	 - Run the app with the command: `npm start`
	 - Your browser should now open a tab with http://localhost:3000
 - For Vue: [get here](https://github.com/vivekanandpv/vue-training-starter)
	 - download, extract, open the inner directory (which has src, package.json) in VS Code
	 - In the integrated terminal, run the command: `npm i`
	 - Run the app with the command: `npm run dev`
	 - Your browser should now open a tab with http://localhost:5173
	 
