# Installation guide

git clone https://github.com/King-Greatman-Spirit/refresh_token_authentication.git

#Setup Backend
1. cd API-Authentication/backend
2. virtualvenv # Create a virtual environment
3. source venv/bin/activate # Activate venv on macOS.
4. source venv/Script/activate # Activate venv on windows.
5. pip install -r requirements.txt
6. python manage.py createsuperuser
7. python manage.py runserver

#Setup Frontend

1. cd API-Authentication/frontend
2. npm install
3. npm start
