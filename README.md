## 🌟Installation
#### 1. Create virtual environment.
```bash
# Windows and Linux
$ python -m venv .venv
```
#### 2. Activate virtual environment.
```bash
# Windows
$ .venv\Scripts\Activate.ps1

# Linux
$ source .venv/bin/activate
```
#### 3. Install all the requirements.
```bash
# Windows and Linux
$ python -m pip install -r requirements.txt
```
#### 4. Run the web in the local server
```bash
# Windows and Linux
$ python manage.py makemigrations
$ python manage.py migrate
$ python manage.py runserver
```
#### 5. To create superuser.
```bash
# Windows and Linux
$ python manage.py createsuperuser
```