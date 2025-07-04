# Healthcareplatformproject
A basic healthcare platform website 

setup for the healthcare/settings.py file before running the platform

SECRET_KEY = ''
enter the django secret key used for cryptographic signing

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': '', # enter your database name here
        'USER': '', # enter your database user here
        'PASSWORD': '', # enter your database password here
        'HOST': 'localhost',
        'PORT': '3306',
    }
}


EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
EMAIL_HOST_USER = ''# enter your host email here
EMAIL_HOST_PASSWORD = ''# enter your host email password here 
