## Intro
Just a simple practice repo for learning Python connections to PostgreSQL.

## Learnings:
- Install PostgreSQL on Windows Subsystem for Linux (WSL)
- Set up User and Database on PostgreSQL.
- Check basic security measures and enable access to PostgreSQL from outside localhost. (From Windows host machine, as the DB is hosted on WSL)
- Create a simple Python script to connect to the PostgreSQL database and perform basic operations using SQLAlchemy.
- Take some random data from a CSV file and insert it into the database.
- Perform some basic queries on the database using SQLAlchemy and Pandas.

## RESOURCES:

https://harshityadav95.medium.com/postgresql-in-windows-subsystem-for-linux-wsl-6dc751ac1ff3

## Basic Setup:
1. Clone the repo.
2. Create a python virtual environment and install the requirements.
    1. ```python -m venv env```
    2. ```source env/bin/activate``` (for LINUX)
    3. ```pip install -r requirements.txt```
3. Create a database in PostgreSQL.
4. Clone the ```config.py.sample``` file and rename it to ```config.py```.
5. Fill the necessary details in the ```config.py``` file.
6. Run the ```analysis.ipynb``` file to see the results.