# Minima Structure
## Ubuntu

- virtualenv (same nome of project_name)
  + create terminal 'python3 -m venv ~/.(PROJECT-NAME)'
  + activate 'source ~/.(PROJECT-NAME)/bin/activate'
  + check 'which pyhton' debe estar python en dir
- requirements.txt (debe tener todas las librerias base)
  + si no se cuenta con Makefile debe ejecutarse 'pip install -r requirements.txt'
- Makefile: 'make install'
- Ipynb: set virtual env as kernek: 'ipython kernel install --name ".(PROJECT-NAME)" --user'

## Windows

- Step 1: Open PowerShell and navigate to your project directory    
`cd path\to\your\project`    
- Step 2: Create the virtual environment directory   
`mkdir .venv`   
- Step 3: Mark the directory as hidden   
`attrib +h .venv`    
- Step 4: Create the virtual environment   
`python -m venv .venv`   
- Step 5: Activate the virtual environment
`.\.venv\Scripts\Activate`       
- Step 6: Add .venv to .gitignore   
`echo .venv >> .gitignore`    

# Poetry 
- use files: `poetry.lock` and `pyproject.toml` (see:https://python-poetry.org/docs/basic-usage/)
