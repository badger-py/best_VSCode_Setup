# best_VSCode_Setup
Best VSCode Setup (my opinion)
To install this setup you just need to install this extensions in your VSCode:

Atom One Dark Theme
TODO Highlight
vscode-icons
Spelling Checker for Visual Studio Code

If you are frontend:
  Auto Rename Tag
  IntelliSense for CSS class names in HTML
  Live Server
 
If you code in Python: autoDocstring: VSCode Python Docstring Generator

Add this to your config:

```jsonc
{
    "workbench.colorTheme": "Atom One Dark", // theme
    "workbench.iconTheme": "vscode-icons", .// icons
    "window.zoomLevel": 2, // Zoom level
    "files.exclude": { // files which you will not see in files tree
        "**/__pycache__": true, // if you code in python
        "**/.pytest_cache": true // if you code in python
    },
    "python.linting.flake8Enabled": true, // enable flake8 (if you code in python)
    "workbench.editor.labelFormat": "medium" // will show paths to a file in tabs
}
```
