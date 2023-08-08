# FastAPI CRUD app

## Clone this repo
Clone this repo from github.
```bash
git clone https://github.com/image-fuse/fastapi-crud.git
```

## Create virtual environment
You can use the built in venv module.
```bash
python -m venv fastrest_env
```

Activate the virtual environment.
```bash
fastrest_env\Scripts\activate.bat
```

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packages.

```bash
pip install -r requirements.txt
```
## Run server.
Now run the uvicorn server.
```bash
uvicorn app.main:app --reload
```
Now you will see that your server is running at [http://127.0.0.1:8000](http://127.0.0.1:8000).

You can also use the Swagger UI that comes with FastAPI to interact at [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)