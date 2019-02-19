# Django Boiler Plate

_A sane project starting point as outlined in [Two Scoops of Django](https://www.twoscoopspress.com/)._

## Gettings Started

### Docker

The `docker-compose` file is present and using the assumption your project will need use Postgres & redis. To create these containers use `docker-compose up` from the project directory (rename any user names/passwords as you see fit)

### Python version and requirements.

Use your preferred environment management tool to create a clean python install and use the following to install the requirements: `pip install -r requirements.txt`

### Starting the dev server

Run the following to get started:
```commandline
export DJANGO_SETTINGS_MODULE="config.settings.local"
python manage.py runserver
```
and you're off to the races!

### Working on your project
Per the guidelines set in TwoScoops:
  * Static files should be placed in a `static` folder at the project level.
  * Templates should be placed in a `templates` folder at the project level.
  * New app directories should be added at the project level (and added to settings.base.PROJECT_APPS).