# Django
we will create "something" using djingo for the first time
omuk-potrika
        -- news
        -- blog
        ...
django-admin.py startproject helloworldproject
helloworldproject/
        manage.py
        helloworldproject/
            __init__.py
            settings.py
            urls.py
            wsgi.py
            django-admin.py startapp helloworldapp
            helloworldapp
        __init__.py
        models.py
        tests.py
        views.py
        helloworldproject/
        manage.py
        helloworldapp
            __init__.py
            models.py
            tests.py
            views.py
        helloworldproject/
            __init__.py
            settings.py
            urls.py
            wsgi.py
            python manage.py runserver
            Validating models...

0 errors found
May 27, 2013 - 00:29:33
Django version 1.5.1, using settings 'helloworldproject.settings'
Development server is running at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
django.httpfrom HttpResponseto ( import).
from django.http import HttpResponse
from django.http import HttpResponse

def index(request):
    return HttpResponse('Hello World!
    import helloworldapp.views
    url(r'^$', helloworldapp.views.index)
    from django.conf.urls import patterns, include, url
import helloworldapp.views

urlpatterns = patterns('',
    url(r'^$', helloworldapp.views.index),
)
