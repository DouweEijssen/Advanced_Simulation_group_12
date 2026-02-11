# Advanced_Simulation_group_12
Advanced simulation project

## Set up instructions
1. clone repository
2. open project in pycharm
3. create own virtual environment
4. install dependencies
    'pip install -r requirements.txt'

## Manage dependencies
When you install a new package, do this in your terminal

pip install <package>
pip freeze > requirements.txt
git add requirements.txt
git commit -m "Update requirements"

## Git Ignore Rules
We ignore 
.venv/          # Everyone uses their own virtual environment
.idea/          # PyCharm settings (different for each person)
__pycache__/    # Python cache files
*.pyc           # Compiled Python files

## Git workflow for the group
Before you start working: pull the latest changes

We all work in our own branch

