$ mkdir NotesBackend && cd NotesBackend
$ python3 -m venv venv_backend
$ source venv_backend/bin/activate

$ pip install fastapi sqlalchemy

# NotesBackend
├── main.py
├── model
│   ├── __init__.py
│   ├── database.py
│   └── models.py
├── requirements.txt
└── schemas.py
