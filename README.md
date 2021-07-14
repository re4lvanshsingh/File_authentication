# Django_assignment

### To Run this project:
    [1] Clone this project
    [2] Make sure mysql is installed in pc
    [3] goto settings.py in auth, and change the user and password

```bash
  DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'new_database',
        'USER': 'ADD YOUR USER NAME HERE',
        'PASSWORD': 'ADD YOUR PASSWORD HERE',
        'HOST':'127.0.0.1',
        'PORT':'3306',
    }
}
  ```

    [4] open terminal and run server by ->


```bash
  python manage.py runserver
```

#### Below the screenshots are added :

###### Successfull Register
![App Screenshot](screenshots\register_success.png)

###### Trying to register with the same email id which gives error
![App Screenshot](screenshots\register_failed.png)

###### Successfull login which gives a "jwt" token valid for 60 min
![App Screenshot](screenshots\login.png)
