There are many editors that can be used to run python code. I like to keep it as simple as possible and maintain a single program interface for all of my program entry
and debugging. My choice for editor/code runner is Visual Studio Code. It can be downloaded from the Visual Studio Code web site [https://code.visualstudio.com/](https://code.visualstudio.com/).

Once downloaded and installed, open VS Code and install the python extensions that will allow you to run the examples inside VS Code without the need to use the terminal. You will need the following VS Code extensions: Python, Pylance, Jupyter, Code Runner, vscode_create_jupyter.

For the majority of coding we can use Jupyter notebooks for running our interactive code that needs no user input. For programs requiring user input we will use a feature of IPython within a regular python file to run the program cell by cell. This will allow us to interact with the program where the regular VS Code interface will not. We use the '#%%" at the start of a cell to indicate the start of a new cell to run within the file.
