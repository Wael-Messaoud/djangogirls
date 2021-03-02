# djangogirls

In your terminal :

1) Run **python manage.py migrate**
2) Run **python manage.py createsuperuser** and fill in the required fields
3) Run **python manage.py runserver**

A first trick to do is open the project in your favourite editor, go to : 

**site-packages** folder ( which is an external library repository) **> django > views > templates > default_urlconf.html** and mess around with it!
A nice example would be to add an anchor tag with a specific id and add a script to access the **admin route**. A possible script would be : 

```
document.getElementById('admin_link').href = window.location + "admin"
```

Check the deployed version :

https://waelmessaoud.pythonanywhere.com/

https://waelmessaoud.pythonanywhere.com/admin (use **wael** as username and **funfun** as the password)


