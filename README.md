### Django CMS demo

This is a djangocms demo site based on ver 3.4.1 LTS release. I have included the database and media in commit to make bit easier for beginners.

Note: Shortly, you will have brief documentation to start using this repo for your next djangocms project.

### Django CMS & Django Framework Version

django-cms==3.4.1
Django==1.8.15

### For developers, From developers
This repositories is for developers only who know how to setup virtual environment and Django project. In case you would like know how to setup virtualenv, browse through [Configure virtualenv and virtualenvwrapper](http://www.sunilsrikumar.com/2016/03/django-multi-site-setup/)

### Dependencies

There is no dependencies as such. You can setup Django CMS using virtual environment or Vagrant. Choice is yours.

## Installation

Run the following commands:
```
mkvirtualenv djcms
git clone https://github.com/sunilsrikumar/djcms.git
cd djcms
pip install -r requirements.txt
python manage.py runserver
```
Django CMS will be now accessible at http://127.0.0.1:8000/ and the admin interface
at http://127.0.0.1:8000/admin/ . SQlite database is also added into repo thus creating superuser
is not mandatory. Admin credentials are:

```
Username: admin
Password: admin

```

## Features List

Available features details are as follow:
* Integrated Bootstrap framework
* One, Two and Three column content
* Carousel image slider
* Blog
* Poll management
* Person/team page
* Contact page
* Dynamic form through admin
* Standard page with editor
* Indexing
* Search across site
* Document management
* Multi-user
* Group
* Multi-site
* Customized permission management for content management
* Google SEO Optimization for - Page title, slug, page description
* Schedule publishing of content Go live & Expiry

## This repositories as a starting point for your project

Since, secret key is public in this repositories, we recommend developer to create your own secret key in case you want to use this repositories as a starting point for your next Django cms project.
Follow this steps to create a new secret key:

Step 1: Login into python prompt
```
$ python
```
Step2: Import necessary package and generate secret key
```
import os
os.urandom(24).encode('hex')
```
This will generate a secret key in hex code.
Now you can replace with existing secret key in settings/dev.py

## Paid development

We offer paid development of [Django CMS](https://django-cms.org/). Just say hello at info@nescode.com to start a discussion.

## Django development company

We are passionate technologists. We offer full stack development and consulting for organizations
with Python, Django framework, Wagtail, Django CMS and PostgreSQL. Drop us a line at info@nescode.com to shape your idea.
