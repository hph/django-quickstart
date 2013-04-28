django-quickstart
=================

Empty django project with a pre configured sqlite3 database to test or start developing new apps in a few seconds.



DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': 'database.db',
    }
}



TIME_ZONE = 'America/Los_Angeles'


MEDIA_ROOT = os.path.join(PROJECT_ROOT, 'media_root',)
MEDIA_URL = '/media/'

STATIC_ROOT = os.path.join(PROJECT_ROOT, 'static_root',)
STATIC_URL = '/static/'


