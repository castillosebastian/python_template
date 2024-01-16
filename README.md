# Minima Structure
- virtualenv (same nome of project_name)
  + create terminal 'python3 -m venv ~/.(PROJECT-NAME)'
  + activate 'source ~/.(PROJECT-NAME)/bin/activate'
  + check 'which pyhton' debe estar python en dir
- requirements.txt (debe tener todas las librerias base)
  + si no se cuenta con Makefile debe ejecutarse 'pip install -r requirements.txt'
- Makefile: 'make install'
- Ipynb: set virtual env as kernek: 'ipython kernel install --name ".(PROJECT-NAME)" --user'

# Poetry 
- use files: `poetry.lock`and `pyproject.toml` (see:https://python-poetry.org/docs/basic-usage/)
