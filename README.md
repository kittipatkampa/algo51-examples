# algo51-examples
Template repo and virtual env for creating AI-powered applications

# Config environment

Clone the repo
```
git clone https://github.com/kittipatkampa/algo51-examples.git
```

If you are on Mac and haven't installed `pyenv`, use this command:
```
brew install pyenv
```
More detail [here](https://formulae.brew.sh/formula/poetry)

We will install python using pyenv. 
```
pyenv install 3.11
pyenv local 3.11
```

More details about pyenv can be found [here](https://github.com/pyenv/pyenv#installation).

Install [poetry](https://python-poetry.org/docs/basic-usage/) to manage python dependencies.
```
brew install poetry
```

**Important** Reload your environment or open a new terminal session to update your python function. 

You will go through the interactive config process.
```
cd algo51-examples
poetry init
```
After this is completed, you will find a file: `pyproject.toml` in your directory.

Install the python dependencies (listed in `pyproject.toml`)
```
poetry install
```

# Work in venv shell
```
poetry shell
```
and you should see the command prompt like so:
```
(algo51-examples-py3.11) $
```

# Jupyter notebook
Simply run:
```
jupyter lab
```

# Streamlit
Try this example:
```
streamlit run simple_app.py 
```
