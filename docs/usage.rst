=====
Usage
=====

To use Django Ariadne JWT in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_ariadne_jwt.apps.DjangoAriadneJwtConfig',
        ...
    )

Add Django Ariadne JWT's URL patterns:

.. code-block:: python

    from django_ariadne_jwt import urls as django_ariadne_jwt_urls


    urlpatterns = [
        ...
        url(r'^', include(django_ariadne_jwt_urls)),
        ...
    ]
