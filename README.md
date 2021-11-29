# Task4
Reinforcement Learning

# Installation
The library Box2D=2.3.10 is not available in this version in python 3.9!
So we need to install python 3.8. We can do this by using `pyenv`.
Alternatively `pipenv`, `conda` also works.

1. install pyenv https://github.com/pyenv/pyenv#installation
2. install python 3.8
   - `pyenv install 3.8.12`
3. load python 3.8 in current shell with
   - `pyenv shell 3.8.12`
     - alternatively set the current directory (and sub dirs) to always use python 3.8.12 with
     - `pyenv local 3.8.12`
   - chek if correct version loaded
      - `pyenv version`
4. create virtual env
   - `python -m venv venv`
5. install requirements
   - `pip install -r requirements.txt`