# VS Code Extensions

## [Extensions I Made](https://marketplace.visualstudio.com/search?term=publisher%3A"Tomas%20Hubelbauer"&target=VSCode)

### [MarkDown To-Do](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.vscode-markdown-todo)

![](https://img.shields.io/visual-studio-marketplace/stars/TomasHubelbauer.vscode-markdown-todo.svg)
![](https://img.shields.io/visual-studio-marketplace/d/TomasHubelbauer.vscode-markdown-todo.svg)
![](https://github.com/tomashubelbauer/vscode-markdown-todo/workflows/.github/workflows/main.yml/badge.svg)

https://github.com/TomasHubelbauer/vscode-markdown-todo

### [MarkDown Table Format](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.vscode-markdown-table-format)

![](https://img.shields.io/visual-studio-marketplace/stars/TomasHubelbauer.vscode-markdown-table-format.svg)
![](https://img.shields.io/visual-studio-marketplace/d/TomasHubelbauer.vscode-markdown-table-format.svg)
![](https://api.travis-ci.org/TomasHubelbauer/vscode-markdown-table-format.svg?branch=master)

https://github.com/TomasHubelbauer/vscode-markdown-table-format

### [ZIP File System](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.zip-file-system)

![](https://img.shields.io/visual-studio-marketplace/stars/TomasHubelbauer.zip-file-system.svg)
![](https://img.shields.io/visual-studio-marketplace/d/TomasHubelbauer.zip-file-system.svg)

https://github.com/TomasHubelbauer/vscode-zip-file-system

### [MarkDown Table of Contents](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.markdown-table-of-contents)

![](https://img.shields.io/visual-studio-marketplace/stars/TomasHubelbauer.markdown-table-of-contents.svg)
![](https://img.shields.io/visual-studio-marketplace/d/TomasHubelbauer.markdown-table-of-contents.svg)

https://github.com/TomasHubelbauer/vscode-markdown-table-of-contents

### [MarkDown Box Drawing](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.vscode-box-drawing)

![](https://img.shields.io/visual-studio-marketplace/stars/TomasHubelbauer.vscode-box-drawing.svg)
![](https://img.shields.io/visual-studio-marketplace/d/TomasHubelbauer.vscode-box-drawing.svg)
![](https://api.travis-ci.org/TomasHubelbauer/vscode-box-drawing.svg?branch=master)

https://github.com/TomasHubelbauer/vscode-box-drawing

### [Week Number](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.vscode-week-number)

![](https://img.shields.io/visual-studio-marketplace/stars/TomasHubelbauer.vscode-week-number.svg)
![](https://img.shields.io/visual-studio-marketplace/d/TomasHubelbauer.vscode-week-number.svg)
![](https://api.travis-ci.org/TomasHubelbauer/vscode-week-number.svg?branch=master)

https://github.com/TomasHubelbauer/vscode-week-number

### [MarkDown Email Links](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.vscode-markdown-email-links)

![](https://img.shields.io/visual-studio-marketplace/stars/TomasHubelbauer.vscode-markdown-email-links.svg)
![](https://img.shields.io/visual-studio-marketplace/d/TomasHubelbauer.vscode-markdown-email-links.svg)
![](https://api.travis-ci.org/TomasHubelbauer/vscode-markdown-email-links.svg?branch=master)

https://github.com/TomasHubelbauer/vscode-markdown-email-link

### [MarkDown Jira Links](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.markdown-jira-links)

![](https://img.shields.io/visual-studio-marketplace/stars/TomasHubelbauer.markdown-jira-links.svg)
![](https://img.shields.io/visual-studio-marketplace/d/TomasHubelbauer.markdown-jira-links.svg)

https://github.com/TomasHubelbauer/vscode-markdown-jira-links

### [Email Viewer](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.email-viewer)

![](https://img.shields.io/visual-studio-marketplace/stars/TomasHubelbauer.email-viewer.svg)
![](https://img.shields.io/visual-studio-marketplace/d/TomasHubelbauer.email-viewer.svg)
![](https://api.travis-ci.org/TomasHubelbauer/vscode-email-viewer.svg?branch=master)

https://github.com/TomasHubelbauer/vscode-email-viewer

### [MarkDown Link Suggestions](https://marketplace.visualstudio.com/items?itemName=TomasHubelbauer.vscode-markdown-link-suggestions)

![](https://img.shields.io/visual-studio-marketplace/stars/tomashubelbauer.vscode-markdown-link-suggestions.svg)
![](https://img.shields.io/visual-studio-marketplace/d/tomashubelbauer.vscode-markdown-link-suggestions.svg)
![](https://travis-ci.org/TomasHubelbauer/vscode-markdown-link-suggestions.svg?branch=master)

https://github.com/TomasHubelbauer/vscode-markdown-link-suggestions

## Extensions I Want To Make

- [VS Code Video](https://github.com/TomasHubelbauer/vscode-video)

## Extension Quickstart

The VS Code documentation articles are too talkative, so I'm keeping my own guide:

1. Create a GitHub repository for the extension
2. Close the GitHub repository
3. Run `npx yo code`
4. Answer *TypeScript* to the extension type
5. Enter the human-friendly name of the extension
6. Enter the extension ID (URL slug etc.)
7. Enter the extension description
8. Decline initializing a Git repository - already have one
9. Select *npm* for the package manager
10. Move the files from the directory to the root of the repository
11. Delete the now empty directory and `.yo-repository`
12. Add `node_modules` to a new `.gitignore`
13. Run `npm install` and then press F5 to run the extension debugger

API docs: https://code.visualstudio.com/api

## To-Do

### Replace telemetry with a local bug reporter

Would prompt the user to allow/disallow saving crash report files which could then
be attached to GitHub issues which I would open prefilled for the user.

### Create a template for automated deployment and integrate it in the extensions
