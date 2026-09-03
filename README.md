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


# questions 
1. what is CPU bounds works (file upload in python)
2. where i store my image or other upladed documents.