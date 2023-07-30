![Made with - python](https://img.shields.io/static/v1?label=Made+with&message=python&color=darkgreen&logo=python&logoColor=green)
[![Made with - django](https://img.shields.io/badge/Made_with-django-2ea44f?logo=django&logoColor=green)](https://www.djangoproject.com/start/)
[![Made with - VSCode](https://img.shields.io/static/v1?label=Made+with&message=VSCode&color=blue&logo=Visual+Studio+Code&logoColor=blue)](https://code.visualstudio.com/)
[![Github - service](https://img.shields.io/static/v1?label=Github&message=service&color=black&logo=github&logoColor=black)](https://github.com/)
[![hosting price - 8 USD monthly](https://img.shields.io/static/v1?label=hosting+price&message=8+USD+monthly&color=2ea44f&logo=pythonanywhere)](https://)
[![transactional - email](https://img.shields.io/static/v1?label=transactional&message=email&color=2ea44f&logo=mailgun)](https://www.mailgun.com/)
[![Made with - HTML](https://img.shields.io/static/v1?label=Made+with&message=HTML&color=orange&logo=html5&logoColor=orange)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Made with - CSS](https://img.shields.io/static/v1?label=Made+with&message=CSS&color=blue&logo=CSS3&logoColor=blue)](https://developer.mozilla.org/en-US/docs/Web/CSS)
# TodoApp

By following [tutorial](https://www.pythontutorial.net/django-tutorial/) about [Django](https://www.djangoproject.com/start/) was created the project [TodoApp](http://todoapp-nazar2022.pythonanywhere.com/).
Not bad idea for good understanding and practicing with this framework.

The hardest was deploy and run this on the web server and sync it with [SMTP server](https://www.techtarget.com/whatis/definition/SMTP-Simple-Mail-Transfer-Protocol) to implement password recovery functionality via transactional emails and API service.
👉 Click [here](http://todoapp-nazar2022.pythonanywhere.com/) to see WebApp online.

# How it works

<img width="467" alt="Знімок екрана 2023-07-27 122029" src="https://github.com/Nazar-Pichak/TodoApp/assets/103797791/ef7210be-3f8d-4705-a256-ffff5436d485">

# Web Services

- [Pythonanywhere](https://www.pythonanywhere.com/) as a hosting service.
- [Mailgun](https://www.mailgun.com/) as a smtp server with simple API integration for the most popular programming languges.

# Installation

```
python -m venv env
.\env\Scripts\activate
git clone https://github.com/Nazar-Pichak/TodoApp.git

```
- cd to the folder where the repo was cloned

```
python -m pip install --upgrade pip
pip install -r requirements.txt
python manage.py runserver
```