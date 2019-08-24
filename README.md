# Installing
---

### Clone the project

```
git clone git@github.com:ryand91/webapp.git
cd webapp
```

### Install dependencies & activate virtualenv

```
python3 -m venv DjangoApp
source DjangoApp/bin/activate
pip install django
pip install django-bootstrap4

```

### Apply migrations

```
python src/manage.py migrate
```

### Running

Just run this command:

```
python src/manage.py runserver
```