# vsctuto

Visual Studio Code Tutorial for Data Scientists and Statistical Programmers.

## Visual Studio Code

Visual Studio Code (VS Code) is a lightweight, free code editor developed by Microsoft. It supports many programming languages and offers a range of extensions to enhance productivity. It provides built-in features like debugging and smart code completion. It also integrates easily with version control systems like Git.

<a href="https://code.visualstudio.com/docs"><img src="img/vscode.png" alt="Visual Studio Code Logo" height="300px" width="auto"></a>

[Visual Studio Code Documentation](https://code.visualstudio.com/docs)

### Who is using Visual Studio Code

[shiny](https://github.com/rstudio/shiny) and [matplotlib](https://github.com/matplotlib/matplotlib) are examples of top projects which using Visual Studio Code.

### GitHub Copilot

[GitHub Copilot](https://github.com/features/copilot) transforms the developer experience. Backed by the leaders in AI, GitHub Copilot provides contextualized assistance throughout the software development lifecycle, from code completions and chat assistance in the IDE (Integrated Development Environment) to code explanations and answers to docs in GitHub and more. With GitHub Copilot elevating their workflow, developers can focus on: value, innovation, and happiness.

GitHub Copilot is avaialable by [Chat](https://github.com/copilot) or can be integrated in your IDE like Visual Studio Code.

## Tutorial

Your job will be to set up the Visual Studio Code environment and save the world.

![Source: Springer Nature](img/virus.png)

You are a scientist and you have to save the world from epidemy.
Your company designed 3 drugs and you have to check if any of them works.
Your task is to choose which drug is working using the data from the first trial.
However first you have to set up your Visual Studio Code environment.

Please Use Python or R.

Please refer to [python_codespace](https://www.github.com/polkas/python_codespace) or [r_codespace](https://www.github.com/polkas/r_codespace) repositories with .vscode and .devcontainer directories. Each repository contains two key configuration folders. The .vscode folder contains environment-specific JSON files for editor settings, debugging configurations, and task automation. The .devcontainer folder holds the container configuration to build a consistent, reproducible development environment.

Checklist for Success:

* Fork the vsctuto repository on GitHub.

Visual Studio Code Settings

* Please use GitHub "Fn + ." to access web vscode. Stage, Commit and Push the `.vscode/settings.json` and `.vscode/extensions.json` files. Please refer to [python_codespace](https://www.github.com/polkas/python_codespace) or [r_codespace](https://www.github.com/polkas/r_codespace) repositories with `.vscode` and `.devcontainer` directories.
* Close and Open the web vscode session and inspect what changed.
* Create a `LICENSE` file.
* Change an editor `font size` setting and add it to the `settings.json` file. 
* Stage, Commit and Push the changes.


Devcontainer (Secure Cloud Based Solution)

* Please use GitHub "Fn + ." to access web vscode. Set up a devcontainer (.devcontainer/devcontainer.json) for Python or R. Please refer to [python_codespace](https://www.github.com/polkas/python_codespace) or [r_codespace](https://www.github.com/polkas/r_codespace) repositories with .vscode and .devcontainer directories.
* Stage, Commit and Push the changes.
* Run the Codespaces on GitHub.
* Validate your codespace, whether it build successfully.

Analysis

* Load and explore the Trial data in `data/data.csv` using your own analysis script to find out which drug is working. The installed extensions and settings should hint you the function names and format the file on save. You need to installed R or python dependencies like pandas.
* [BONUS] Validate your results with GitHub Copilot. Use GitHub Copilot Agent mode and ask "Please analyze the data in data.csv to determine which drug has the highest cure rate compared to the placebo. Update the [Python|R] script if necessary, and ensure the correct result is written to solution.txt.". You can further ask about, for example effect size.
* Perform the statistical analysis to identify if any drug is working. Please write down a string with a name of working drug in the `solution.txt` file, "Drug A" or "Drug B" or "Drug C" or "None".
* Stage, Commit and Push your work.

**You SUCCEEDED when GitHub actions pipeline will pass (green color).**



