django-quickstart
=================

Empty django project with a pre-configured sqlite3 database to test or start 
developing new apps in a few seconds.


**Directory**
    
    PROJECT_ROOT = os.path.dirname(os.path.realpath(__file__))

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

**Installed apps**

    INSTALLED_APPS = (
        'django.contrib.auth',
        'django.contrib.contenttypes',
        'django.contrib.sessions',
        'django.contrib.sites',
        'django.contrib.messages',
        'django.contrib.staticfiles',
        # Uncomment the next line to enable the admin:
        'django.contrib.admin',
        # Uncomment the next line to enable admin documentation:
        # 'django.contrib.admindocs',

        #Some usefull 3rd party apps
        #'django_extensions',
        #'sorl.thumbnail',
        #'reversion',
        #'south',
        'debug_toolbar',
    )


Contributing
============

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
