## Organisational Charts

A multidepartment organisational chart django app, based on https://github.com/dabeng/OrgChart. 

### Installation Instructions

#### Requirements

- [Python 3, pip](https://www.python.org/downloads/release/python-361/)
- virtualenv
```
> pip install virtualenv
```

#### Installation (Windows)

- Clone this repository:
```
> git clone https://github.com/Mardirooster/orgchart.git
```
- Set up virtualenv and install requirements:
```
> virtualenv env
> .\envs\orgchart\Scripts\activate
> pip install -r requirements.txt
```

- Initialise database:
```
> python manage.py makemigrations
> python manage.py migrate
```

- Run server:
```
> python manage.py runserver
```


(Currently project is set up to run with Postgres & IIS)