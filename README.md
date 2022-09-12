# Django_blog
blog website using django framework also provided admin panel , where you can control , write and modify blogs ..


### To run this project 

1. clone into your local machine :  ``` git clone https://github.com/ashu1281/Django_blog.git```
2. go to project using ```cd django_blog```
3. go to inside folder ```cd django_blog ```
4. now to install and activate virtual environment type command : ``` pipenv shell```
5. Now install django to your inside the virtual environment : ``` pipenv install django ```
6. Now run this project using : ```python manage.py runserver ``` 
7. head over to http://127.0.0.1:8000/ to see the output
8. You will see the output window : 
![image](https://user-images.githubusercontent.com/98692616/178452789-fd177850-93b5-4d77-9b70-042ba22ea2c3.png)
### Now you only see the blog but you will not able to write or modify or delete . 

for that you need to access the admin , for this you need to create a superuser and provided the login information and login ..

1. to create a super user run ``` python manage.py createsuperuser```  
3. This will ask you  username :
  
                      password :                    
                      Email :
                      
3. run again ```python manage.py runserver ```

4. Now to go http://127.0.0.1:8000/admin/ and login with your username and password .

5. output : 
![image](https://user-images.githubusercontent.com/98692616/178713400-2e9a5531-00af-4083-954c-69eeb5151b14.png)
Now you can add blog , delete and update the blog posts..

6. Demo video
        https://www.youtube.com/watch?v=KcWv2urjFMw



for any query connect to linkedin www.linkedin.com/in/ashishggaikwad
