1. uv init PROJECT_NAME
2. cd PROJECT_NAME
3. uv add "fastapi[standard]"

to run this applications use
uv run fastapi dev main.py

need to install the sqlalchemy
uv add sqlalchemy

need to install another package in tutorials 7 which is aiosqlite => sqlite can this package for async oparations.

uv add aiosqlite

and also need to install the 
uv add greenlet
#### for authentication need to install 2 pakages which is 
uv add "pwdlib[argon2]"
uv add pyjwt
uv add pydantic-settings

#### for file upload need to install the pillow pagkages
uv add pillow

#### for password validations need to install this 
uv add aiosmtplib

#### for db install this 
uv add "psycopg[binary]"

#### database migration tool
uv add alembic
uv run alembic init -t async alembic


#### for migations the data
1. uv run alembic revision --autogenerate -m "initial schema"

<!-- for upgrade the file head -->
2. uv run alembic upgrade head
<!-- for check the current migrate status -->
uv run alembic current


# questions 
1. what is CPU bounds works (file upload in python)
2. where i store my image or other upladed documents.
3. please also check the fastapi pagination library
4. what is smtp server to send the email (send gred or AWS)
5. what is compare type in alembic?

#### to run the postgresql in the git bash run this 
1. export PATH="/c/Program Files/PostgreSQL/18/bin:$PATH"
2. psql --version