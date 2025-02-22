## to create virtual environment
C:\git\p2025b> python -m venv .venv

## to create virtual environment for specific python version
C:\git\p2025b> py -0
C:\git\p2025b> py -3.12 -m venv .venv

## to install langflow
(.venv) C:\git\p2025b> python -m pip install langflow

## to check langflow version
(.venv) D:\git\p2025b\p2025b>pip show langflow

## to backup package installation info
(.venv) C:\git\p2025b> pip freeze > requirements.txt
