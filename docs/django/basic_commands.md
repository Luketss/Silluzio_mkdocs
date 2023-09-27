

run the Django command-line utilities to create the database tables automatically:

``` bash
$ python manage.py makemigrations # (1)
```

1.  🙋 The `makemigrations` command __looks at all your available models__ and creates migrations for whichever tables don’t already exist. 

``` bash
$ python manage.py migrate # (1)
```

1.   `migrate` runs the migrations and creates tables in your database, as well as optionally providing much richer schema control.
