# PythonDevTutorial

## Description

This is the note about how to development python before startup. </br>
Hope it can help you when using python to development. :) </br>


### How to setup the virtual environment when development python ?
python -m venv \<virtual-environment-folder-name\> </br>
Ex. `python -m venv env` </br>

* Enable Virtual environment </br>
`env/Scripts/activate.bat` </br>

* Disable Virtual environment</br>
`env/Scripts/deactivate.bat` </br>

* How to check the modules that you install in virtual environment </br>
`python -m pip list` </br>


### Install Ruff to be Linter for format and error check
`python -m pip install ruff`

### Install Pre-commit to check the code when commit the code
`python -m pip install pre-commit`



### Refer to
* [Makedown Formant](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Virtual Environment](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/)
* [Ruff](https://myapollo.com.tw/blog/python-linter-ruff/)
* [Ruff](https://blog.kyomind.tw/ruff/)
* [Pre-commit](https://blog.kyomind.tw/pre-commit/)
