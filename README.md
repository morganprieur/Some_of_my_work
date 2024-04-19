
# Some of my work 

Some authorized of my projects and contributions, both professionals and personals. The data from the pros projects may be anonymized for some obvious reasons. 

---- 
## Literary Reviews 
**Python**     
Django network like application allowing to request and write books' and articles' reviews. 

Logged in users are allowed to follow others users by their username, or block them. They can see the posts of their followed users, and their own posts. 
They are also able to:
- write tickets to request for an article or book review, 
- write a review answering to a ticket, 
- write a review and the ticket at the same time.

This application respects accessibility (WCAG) and eco-design ("Green code") rules. 

[Repo](https://github.com/morganprieur/Literary_reviews/tree/main) 


##### Techonolgies 
* Python 
* Pipenv 
* Django 
* WCAG 
* Ecoconception 
* W3CSS 
* Flake8 

---- 
## Projects Management API 
**Python**     
Django RestFramework B2B support API. 
It allows to manage users, projects, issues and issues' comments. Authentication is ensured by JWT. The users chose to share or not their data, and to be contacted or not, and they are allowed to manage their choices when they want it. 
The logged in users can create projects, issues, and issues' comments, and manage their own objects. Some entities get created automatically when a trigger happens. 

The API respects "green code" of "INR" and some rules of the GDPR about the users' data. 

The documentation has been generated with DRF Spectacular. 

The (PostgreSQL) DB and the API are running into different Docker containers. 

[Repo](https://github.com/morganprieur/Projects_management_API) 

##### Techonolgies 
* Python 
* Pipenv 
* djangorestframework-simplejwt 
* Django-simple-jwt 
* DRF-spectacular / Swagger 
* Flake8 
* Docker 

---- 
## Test Flask Registration MVP 
**Python**     
Tests on an existing registration MVP application in Flask. 
[Repo](https://github.com/morganprieur/Tests_flask) 

##### Techonolgies 
* Python 
* Pipenv 
* Flask 
* Pytest
* Coverage 
* Locust 
* Flake8 

---- 
## Itf Web 
**Javascript**     
Get the data from a given API, to display them into the browser, like on Netflix. 
Display management with Javascript. The CSS is developped with Sass and displayed with the W3CSS framework. 
The project is developped into a Docker container. 
[Repo](https://github.com/morganprieur/itf_web) 

##### Techonolgies 
* Javascript 
* HTML 
* CSS 
* SASS 
* W3CSS 
* Docker 

---- 
## Backend Python SQL 
**Python**     
CLI backend CRM application. Developped with Python (without framework) and PostgreSQL. 
It allows to manage users, authorizations with tokens, read, create and update clients, contracts and events, depending of the authorizations. "Admin" users are allowed to manage the other users. 

The PostgreSQL database is developped into a Docker container. 

[Repo](https://github.com/morganprieur/backend_python_sql) 

##### Techonolgies 
* Python 
* Pipenv 
* PostgreSQL 
* SQLAlchemy 
* Bcrypt 
* Cryptography 
* prompt-toolkit 
* Pytest 
* Coverage 
* Flake8 
* Docker 

---- 
## Sites Watch 
**Python**     
Flask MVP that allows to see the remote cameras views. Login required, home page displays a dashboard. 
User management: admins can manage users, clients can only see the cameras and views. 

[Repo](https://github.com/morganprieur/site_watch) 

##### Techonolgies 
* Python 
* Pipenv 
* JSON 
* Flask_bcrypt 
* Flake8 

---- 

## Tcom MVP 
**Python** 
Application de visualisation et gestion de travaux. Accès aux documents nécessaires, géolocalisation des sites, upload de photos. 
Gestion des accès utilisateurs : nécessité de posséder un compte pour se connecter. Un compte "démo" peut être créé. 
Le front est adapté aux mobiles. 

Disclaimer : Adaptation d'un projet réel. Toutes les informations sensibls ont été retirées ou anonymisées. Il peut en résulter des erreurs. Ne pas utiliser tel quel, et envoyez un feedback en cas de problème. 

L'application est développée dans des containers Docker : 
    - la BDD -> container "db_tcom" 
    - l'application -> container "app_tcom" 
    - Adminer (gestion de la BDD) -> container "adminer_tcom" 

[Repo](https://github.com/morganprieur/tcom_mvp) 

##### Techonolgies  
Django 
PostgreSQL 
Signal (Django) 
JWT 
Pillow (gestion des images) 
Django template 
Bootstrap 
Docker 

---- 
## API_systems 
**Python** 
API permettant de consulter les données enregistrées pour les systèmes installés et configurés. Les techniciens peuvent enregistrer les systèmes avant de les mettre en service. 

Disclaimer : Adaptation d'un projet réel. Toutes les informations sensibls ont été retirées ou anonymisées. Il peut en résulter des erreurs. Ne pas utiliser tel quel, et envoyez un feedback en cas de problème. 

La BDD et l'API sont dans des containers Docker gérés par un fichier compose.yaml : 
    BDD -> container "db" 
    API -> container "api" 

[Repo](https://github.com/morganprieur/API_systems) 

**Technologies** 
Django 
PostgreSQL 
Django Signals
JWT 
Django permissions 
Docker 

---- 
## Prepa Meeting 
**PHP**     
PHP CodeIgniter application to view and manage subjects into a dashboard. Database MySQL. Subject export into CSV or PDF. 
[Repo](https://github.com/morganprieur/prepa-meeting) 

##### technologies 
* PHP 7 
* CodeIgniter 4 
* MySQL 
* CSV 
* DomPDF 

---- 
## Contributed to a historical research project (2021) 
**PHP**     
Project that stores more than 60,000 data of marriage acts from Buenosaires, for historical research use. It allows to view and manage the data through a browser interface and export pieces of data. 
[Buenosaires Repo](https://github.com/githof/buenosaires) 

##### technologies 
* PHP (without framework) 
* MySQL / MariaDB 
* CSV 
* HTML 
* CSS 
* Bootstrap 

---- 

