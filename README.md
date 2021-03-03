# djangogirls

In your terminal :

1) Run **python manage.py migrate**
2) Run **python manage.py createsuperuser** and fill in the required fields
3) Run **python manage.py runserver**

THe default Django page is located at :

**site-packages** folder ( which is an external library repository) **> django > views > templates > default_urlconf.html**. Mess around with it!
A nice example would be to add an anchor tag with a specific id and add a script to access the **admin route**. A possible script would be : 

```
document.getElementById('admin_link').href = window.location + "admin"
```
You can omit the route definition in mysite/urls for the blog.urls to get the default page.

Check the deployed version :

https://waelmessaoud.pythonanywhere.com/

In order to have access to posts modifications, you need to go to the following link :

https://waelmessaoud.pythonanywhere.com/admin (use **wael** as username and **funfun** as the password) 


