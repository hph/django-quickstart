django-quickstart
=================

Empty django project with a pre configured sqlite3 database to test or start developing new apps in a few seconds.


**Database**

    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.sqlite3',
            'NAME': 'database.db',
        }
    }



**Time zone**

    TIME_ZONE = 'America/Los_Angeles'


**Media and static files**

    MEDIA_ROOT = os.path.join(PROJECT_ROOT, 'media_root',)
    MEDIA_URL = '/media/'
    STATIC_ROOT = os.path.join(PROJECT_ROOT, 'static_root',)
    STATIC_URL = '/static/'


