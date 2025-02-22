## to create virtual environment
C:\git\p2025b> python -m venv .venv

## to create virtual environment for specific python version
C:\git\p2025b> py -0
C:\git\p2025b> py -3.12 -m venv .venv

## to activate virtual environment
C:\git\p2025b> .venv\Scripts\activate

## VS Code에서 자동 설정
1. .venv를 만든 후 VS Code를 다시 시작해.
2. Ctrl + Shift + P를 눌러 명령 팔레트를 열어.
3. "Python: Select Interpreter"를 검색해서 선택해.
4. 목록에서 .venv 폴더 안의 Python 인터프리터를 선택하면 돼!

## to install langflow
(.venv) C:\git\p2025b> python -m pip install langflow

## to check langflow version
(.venv) D:\git\p2025b\p2025b>pip show langflow

## to backup package installation info
(.venv) C:\git\p2025b> pip freeze > requirements.txt
