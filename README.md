# Installing
---

### Clone the project

```
git clone git@github.com:ryand91/webapp.git
cd webapp
```

### Install dependencies & activate virtualenv

```
pip install pipenv

pipenv install
pipenv shell
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