# To run the jupyter notebook

First you have to activate the virtual environment "venv"

    venv/Scripts/activate

Then you can type

    jupyter notebook

or you can start jupyterlab(recommended)

    jupyter lab

to activate the notebook

after installing and during work if you need to add another package, for example: requests etc. you have to do this:

    pip install requests

after that you have to update the requirements.txt file with this:

    pip freeze | Select-String requests >> requirements.txt

so, it will automatically append the requirements.txt file with the new addition from "pip list"
# Basic shortcuts for ease of use

1. ESC : select a cell to command mode from writing mode
2. Enter/Return: select a cell to writing mode
3. Ctrl + Return : execute cell
4. shift + return: execute cell and shift focus to the next one, could be handy if you are executing multiple cells in one go and want to see it run properly step by step.
5. D x 2: Press D twice to remove or delete a cell.(in command mode)
6. c: copy a cell (in command mode)
7. v: paste a cell (in command mode)
8. x: cut a cell (icm)
9. z: undo (icm)
10. a: starts a new window on top of the currently focused window
11. b: starts a new window on bottom of the currently focused window
12. m: markdown mode
13. y: python mode