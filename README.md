Web blog
========

[Original course code](https://github.com/schoolofcode-me/web_blog/releases/tag/v1.0.0) | [Code updated to Flask 2.0](https://github.com/schoolofcode-me/web_blog/releases/tag/v2.0.0)

This is a simple web-based blog that doesn't do much but introduces Flask, HTML, CSS, Bootstrap, Jinja2, and other concepts such as endpoints and APIs.

The blog requires MongoDB to be running without authentication enabled.

Once this is running, execute the app with `flask run` and navigate to the endpoint (default: `http://127.0.0.1:5000/`).

The available endpoints are:

- `/`
- `/login`
- `/register`
- `/blogs`
- `/blogs/new`
- `/posts/<string:blog_id>`
- `/posts/new/<string:blog_id>`


## How to use this code

1) Create a new virtual environment: `python -m venv .venv`
2) Activate the virtual environment:

In powershell:

```powershell
.\.venv\Scripts\activate
```

In bash

```bash
source .venv/Scripts/activate
```

In CMD

```cmd
.venv\Scripts\activate
```

In Mac OS / Linux:

```bash
source .venv/bin/activate
```

3) Verify that the file `.flaskenv` is in the top directory and that it contains the environment variable `FLASK_APP=src.app`.

4) Run the app

```
flask run
```
