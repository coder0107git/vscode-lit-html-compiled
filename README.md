# vscode-lit-html-compiled

## About

### What is this?
This repo contains the compiled code from the vscode lit-html extension.

### Why?
Currently Stackblitz Codeflow only has a limited number of extensions built-in (and this extension isn't one of the few built-in ones). This repo holds the extension in a format that can be installed from Stackblitz Codeflow.

## Installation
On Stackblitz Codeflow, do the following: 

1. Open the command palette (<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>)
2. Search for and select `Developer: Install Extension from Location`
3. Enter in the following url: `https://raw.githubusercontent.com/coder0107git/vscode-lit-html-compiled/main/lit-html.vsix.zip/extension/`
4. Enjoy lit syntax

## Update

### Stackblitz Codeflow
Updates should automatically available in Stackblitz Codeflow when this repo is updated.

### This repo
1. Fork & clone the repo
2. Open [the extension](https://marketplace.visualstudio.com/items?itemName=bierner.lit-html) in the VSCode Marketplace
3. Click the `Download Extension` link and save it as a zip
4. Delete the contents of the  `lit-html.vsix.zip/` folder
5. Extract the zip to `lit-html.vsiz.zip/` folder
6. Push your changes and create a pull request
