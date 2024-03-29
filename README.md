# Backend for Reddit clone

Backend API for Reddit clone which has user login, posting, comment, etc...

## Installation

We assume that you have Python and Pip in your machine. If not then go install them first.

This installation is for Window, other platform may have slightly different syntax.

First you need to create a virtual environment

```bash
source> cd backend-reddit-clone
source/backend-reddit-clone> python -m venv venv
source/backend-reddit-clone> cd venv/Scripts
```

Activate virtual machine (IMPORTANT!!)

```bash
source/backend-reddit-clone/venv/Scripts> activate
```

Then you install django and other modules

Remember to activate virtual environment.

```bash
(venv) source/backend-reddit-clone> pip install -r requirements.txt
```

## Migrate the database

Remember to activate virtual environment

```bash
(venv) source/backend-reddit-clone> python manage.py makemigrations core
(venv) source/backend-reddit-clone> python manage.py migrate
```

## Get the Server running (at port 8000)

Remember to activate virtual machine

```bash
(venv) source/backend-reddit-clone> python manage.py runserver
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)