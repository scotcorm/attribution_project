# attribution_project

> An attribution database, especially for images with CC Licenses. 


Description: A database to hold citations records, particularly for images that have Creative Commons licenses.  It can be time-consuming to create correctly-formatted citations, and the goal of this database is to help with initial use, and to encourage re-use of images by making them easy to find.


If you haven't heard of Creative Commons, they offer free licenses that define how works can be shared.  Where Copyright means "all rights reserved", a Creative Commons license can mean "some rights reserved."  https://creativecommons.org


## Structure
```sh
|--src
|  |-attribution_list
       |-asgi.py
       |-settings.py
       |-tests.py
       |-urls.py
       |-wsgi.py
|  |-attributions
       |-templates
           |-attributions
                |-home
       |-admin.py
       |-apps.py
       |-models.py
       |-views.py
   |-github_collab
   |-media
   |-venv
|--db.sqlite3
|--manage.py
|--pytest.ini
|requirements.txt

```
