
## Run Locally

Clone the project

```bash
  git clone https://github.com/ayyaninam/ofty-backend.git
```

Go to the project directory

```bash
  cd ofty-backend
```

Create Virtual environment

```bash
  python -m venv env
```

Activate the ENV (mac, linux)

```bash
  source env/bin/activate
```

Activate the ENV (window)

```bash
  env/Scripts/activate.bat
```

Install Requirements

```bash
  pip install -r requirements.txt
```

Make Migrations

```bash
  python3 manage.py makemigrations
```


Make Migrations

```bash
  python3 manage.py migrate
```


Open new Terminal and Run Redis

```bash
  redis-server
```


Open new Terminal and Run Celery

```bash
  celery -A api_ofty worker -l info 
```


Run the Project

```bash
  python3 manage.py runserver 
```
