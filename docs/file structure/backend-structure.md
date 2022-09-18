# File structure overview for backend

```
.
└── manage.py/
    ├── license.txt
    ├── stories/
    │   ├── views.py
    │   ├── serializers.py
    │   ├── __init__.py
    │   ├── urls.py
    │   ├── admin.py
    │   ├── apps.py
    │   ├── tests.py
    │   ├── signals.py
    │   └── models.py
    ├── .ebignore
    ├── templates/
    │   └── mail/
    │       ├── send-request.html
    │       ├── base.html
    │       ├── standard-link-mail.html
    │       └── activation.html
    ├── .github/
    │   └── ISSUE_TEMPLATE/
    │       └── bug_report.md
    ├── utils/
    │   ├── pagination.py
    │   ├── dbfunctions.py
    │   ├── custombackend.py
    │   ├── custommanagers.py
    │   ├── custompathconverters.py
    │   ├── choicefields.py
    │   ├── customserializers.py
    │   ├── imaging.py
    │   ├── frontend_routes.py
    │   ├── mailing.py
    │   ├── custommodalfields.py
    │   └── custompermissions.py
    ├── category/
    │   ├── views.py
    │   ├── serializers.py
    │   ├── __init__.py
    │   ├── urls.py
    │   ├── admin.py
    │   ├── apps.py
    │   ├── tests.py
    │   ├── signals.py
    │   └── models.py
    ├── readme.md
    ├── .vscode/
    │   ├── settings.json
    │   └── .prettierrc.json
    ├── Procfile
    ├── adostrings/
    │   ├── views.py
    │   ├── s3storage.py
    │   ├── __init__.py
    │   ├── urls.py
    │   ├── asgi.py
    │   ├── wsgi.py
    │   └── settings.py
    ├── user/
    │   ├── views.py
    │   ├── serializers.py
    │   ├── __init__.py
    │   ├── urls.py
    │   ├── djoser_mails.py
    │   ├── tokenserializer.py
    │   ├── admin.py
    │   ├── apps.py
    │   ├── tests.py
    │   ├── signals.py
    │   ├── models.py
    │   └── custom_authentication.py
    ├── requirements.txt
    ├── .gitignore
    ├── .elasticbeanstalk/
    │   └── config.yml
    ├── admin_mailing/
    │   ├── __init__.py
    │   ├── admin.py
    │   ├── apps.py
    │   ├── signals.py
    │   └── models.py
    ├── .ebextensions/
    │   ├── django.config
    │   ├── 01_setup.config
    │   ├── 04_logs.config
    │   └── setvars.config
    └── .platform/
        ├── nginx/
        │   └── conf.d/
        │       └── proxy.conf
        └── 00_myconf.config
```