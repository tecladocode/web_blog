Web blog
========

This is a simple web-based blog that doesn't do much but introduces Flask, HTML, CSS, Bootstrap, Jinja2, and other concepts such as endpoints and APIs.

The blog requires MongoDB to be running without authentication enabled.

Once this is running, execute the app and navigate to the endpoint (default: `http://127.0.0.1:4995/`).

The available endpoints are:

- `/`
- `/login`
- `/register`
- `/blogs`
- `/blogs/new`
- `/posts/<string:blog_id>`
- `/posts/new/<string:blog_id>`


## HOW TO USE THIS CODE

1) Create a new virtual environment: `python -m venv venv`
2) Activate the virtual environment:

In powershell:

```powershell
.\venv\Scripts\activate
```

In bash:

```bash
source venv/Scripts/activate
```

In CMD

```cmd
venv\Scripts\activate
```

3) Set a new environment variable to allow Application Discovery ([more info](https://flask.palletsprojects.com/en/2.0.x/cli/#application-discovery)).

In Powershell

```powershell
$env:FLASK_APP = "src.app"
```

In bash:

```bash
export FLASK_APP=src.app
```

In CMD

```cmd
set FLASK_APP=src.app
```

4) Run the app

```
flask run
```