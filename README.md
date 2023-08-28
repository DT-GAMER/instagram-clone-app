## Django Instagram Clone
Instagram clone using python django with a lot of Instagram features.

## Preview
![Home Page](https://github.com/MurariSabavath/instagram-clone/blob/d7d525fc867b9192c66f28e729e3ce1b365bb836/img/home.png)
![Profile Page](https://github.com/MurariSabavath/instagram-clone/blob/d7d525fc867b9192c66f28e729e3ce1b365bb836/img/profile.png)

#### Give a star if you like it.
## Features
- User authentication(Sign up and sign in).
- Password Reset using email.
- Posting Images.
- Like and comment on a post.

### Installation
- Make sure Python is installed.
- Clone the repository and change your directory to Instagram_clone.
- Install requirements using following command.
```
pip install -r requiremnts.txt
```
### Usage
- Create a ``.env`` file.
- Declare following environment variables in the .env file.
```
> SECRET_KEY = 'secret key'
> DEBUG = True
> EMAIL_USERNAME = 'your email address'
> EMAIL_PASSWORD = 'your password' 
```
- Now make the migrations.
```
python manage.py migrate
```
- Commit the migrations.
```
python manage.py makemigrations
```
- Create a super user.
```
python manage.py createsuper
```
- Run the app.
```
python manage.py runserver
```
- Open the app at `localhost:8000` or `http://127.0.0.1:8000/`

## Contact Me 
### Abakpa Dominic

[Github](https://github.com/DT-GAMER) <br> 
[Instagram](https://www.instagram.com/dt_gamer01/) <br>
[Gmail](mailto:abakpad82@gmail.com) <br>
[Twitter](https://twitter.com/dominic_abakpa) <br>
