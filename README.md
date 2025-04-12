# vsctuto

Visual Studio Code Tutorial for Data Scientists and Statistical Programmers.

## Visual Studio Code

Visual Studio Code (VS Code) is a lightweight, free code editor developed by Microsoft. It supports many programming languages and offers a range of extensions to enhance productivity. It provides built-in features like debugging and smart code completion. It also integrates easily with version control systems like Git.

<a href="https://code.visualstudio.com/docs"><img src="img/vscode.png" alt="Visual Studio Code Logo" height="300px" width="auto"></a>

[Visual Studio Code Documentation](https://code.visualstudio.com/docs)

## Who is using Visual Studio Code

[shiny](https://github.com/rstudio/shiny) and [matplotlib](https://github.com/matplotlib/matplotlib) are examples of top projects which using Visual Studio Code.

## Tutorial

Your job will be to set up the Visual Studio Code environment and save the world.

![Source: Springer Nature](img/virus.png)

You are a scientist and you have to save the world from epidemy.
Your company designed 3 drugs and you have to check if any of them works.
Your task is to choose which drug is working using the data from the first trial.
However first you have to set up your Visual Studio Code environment.

Please Use Python or R.

Please refer to [python_codespace](https://www.gtihub.com/polkas/python_codespace) or [r_codespace](https://www.gtihub.com/polkas/r_codespace) repositories with .vscode and .devcontainer directories. Each repository contains two key configuration folders. The .vscode folder contains environment-specific JSON files for editor settings, debugging configurations, and task automation. The .devcontainer folder holds the container configuration to build a consistent, reproducible development environment.

Checklist for Success:

* Fork the vsctuto repository on GitHub.

Visual Studio Code Settings

* Create and commit the .vscode/settings.json and .vscode/extensions.json files. PLease use GitHub "Fn + ." to access web vscode.
* Close and Open the web vscode session and inspect what changed.
* Create a LICENSE file.
* CHnage a font size setting and add it to settings.json file.
* Stage, Commit and Push the changes.


Devcontainers steps which you can skip if you are using your local computer

* Set up a devcontainer (.devcontainer/devcontainer.json) for Python or R. 
* Run the Codespaces on GitHub.
* Validate your codespace, whether it build successfully.

Analysis

* Load and explore the Trial data in data/data.csv using your analysis script.
* The installed extensions and settings shuld hint you the function names and format the file on save.
* Perform the statistical analysis to identify if any drug is working.
* Stage, Commit and Push your work.


