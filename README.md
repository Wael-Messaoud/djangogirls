# djangogirls

In case you want to run the project locally. In your terminal :

We are going to follow the best practices and run the project inside a virtual environment. Run commands in your terminal as follows inside a repo :

1) **python3 -m venv myvenv**
2) **source myvenv/bin/activate**
3) **pip install -r requirements.txt** 
4) **python manage.py migrate**
5) **python manage.py createsuperuser** and fill in the required fields
6) **python manage.py runserver**
7) Go to **http://127.0.0.1:8000/admin** and fill in the created superuser details
8) Go back to **http://127.0.0.1:8000**

The default Django page is located at :

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


