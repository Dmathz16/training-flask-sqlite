# Flask SQLite

A simple flask application from the [documentation](https://flask.palletsprojects.com/en/3.0.x/tutorial/).

## Requirements
Windows:
* [python](https://www.python.org/downloads/)
  
## How to run?
Windows:
1. Make sure the requirements are installed and running.
2. Clone/download then extract this project.
3. Open cmd/terminal then cd to this project.
   ```cmd
   cd PATH_OF_THE_PROJECT
   ```
4. Generate virtual environment:
   ```cmd
   py -3 -m venv .venv
   ```
5. Activate environment:
   ```cmd
   .venv\Scripts\activate
   ```
6. Install modules:
    ```cmd
   pip install -r requirements.txt
    ```
7. Generate mysql database:
    ```cmd
   flask --app flaskr init-db
   ```
8. Run project:
   ```cmd
   flask --app application run --debug
   ```
9. Done

## Output
![image](https://github.com/Dmathz16/training-python-flask-sqlite/assets/54519505/ef771fda-0d00-4d6b-98b1-fc7343d75172)
