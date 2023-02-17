# [Soft Dashboard PRO Jinja](https://appseed.us/product/soft-ui-dashboard-pro/flask/)

**Jinja/Flask Template** provided by AppSeed on top of **[Soft UI Dashboard PRO](https://appseed.us/product/soft-ui-dashboard-pro/flask/)**, a modern `Bootstrap 5` design from [Creative-Tim](https://bit.ly/3fKQZaL). 
The project might help beginners to code simple presentation websites on top of the existing codebase OR migrate the `production-ready` UI to a legacy Python-based project compatible with **Jinja Template Engine**: *Flask*, *Django*, *Bottle* of *FastAPI*. 

- [Soft Dashboard PRO Jinja/Flask](https://jinja-soft-ui-dashboard-pro.appseed-srv1.com/) - LIVE Demo
- [Soft Dashboard PRO Jinja/Flask](https://appseed.us/product/soft-ui-dashboard-pro/flask/) - Product Page

<br />

> Features:

- ✅ `Up-to-date dependencies`
- ✅ UI Kit: **[Soft UI Dashboard PRO](https://bit.ly/2RtSXVa)** (PRO Version) by **Creative-Tim**
- ✅ `Docker`
- 🚀 `CI/CD` flow via `Render`

<br />

## Quick Start in `Docker`

> Get the code

```bash
$ git clone https://github.com/app-generator/priv-jinja-soft-ui-dashboard-pro.git
$ cd priv-jinja-soft-ui-dashboard-pro
```

> Start the app in Docker

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />

![soft-ui-dashboard-pro-screen](https://user-images.githubusercontent.com/51070104/145958818-b2080e5c-b369-4be6-a1a8-a49727f6f8bb.png)

<br /> 

## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/app-generator/jinja-berry-dashboard.git
$ cd jinja-berry-dashboard
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_DEBUG=False
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_DEBUG=False
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_DEBUG = "False"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |
   |         |-- home/                     # UI Kit Pages
   |              |-- index.html           # default page
   |              |-- page-404.html        # 404 error page
   |              |-- *.html               # Used by common pages like index, UI
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />

---
[Soft Dashboard PRO Jinja](https://appseed.us/product/soft-ui-dashboard-pro/flask/) - Provided by **[AppSeed](https://appseed.us/app-generator)**.
