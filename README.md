# pizarra

## Create Virtualenv:
```console
Windows: python -m venv .venv
Linux: python3 -m venv .venv
```
## Entry Virtualenv:
```console 
Windows: .venv\Scripts\activate
Linux: source .venv\bin\activate
```
## Install libs:
```console
pip install -r requeriments-dev.txt
```
## Rum migrate:
```console
python manage.py migrate
```
## Create user:
```console
python manage.py createsuperuser
```
## Run server:
```console
python manage.py runserver
```

### Done!