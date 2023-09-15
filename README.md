# Business Case: Timothy Stevens is looking to sell and is focused on finding the best timing. He's also open to renovation if it enhances profitability.


## Technical Requirements

- pyenv
- python==3.11.3

## Setup

* set the python version locally to 3.11.3
* create a virtual environment using the `venv` module
* activate your newly created environment 
* upgrade `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* install the required packages via `pip`


### Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies to run files smoothly. Before you install the virtual environment, make sure to install postgresql.

```bash
brew update
brew install postgresql
```

In order to install the environment you can use the following commands:

```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```