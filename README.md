#### Setup


Install [pyenv](https://github.com/pyenv/pyenv) and [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv). Then...


`pyenv install 3.8.0`


`pyenv virtual-env 3.8.0 effective-python`


`echo effective-python > .python-version`


`pip install -r requirements.txt`


#### Execution


`jupyter notebook`

And select the .ipynb file.