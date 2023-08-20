## Django Proj Full Fledge

* `conda create -p venv python==3.8 -y`
* `conda activate venv/`
* `conda env list --json`


```
git init
git add .
git commit -m "message"
git push origin master

if not working then use below cmd:
git push --force origin master

git merge 
git pull origin master/main

New commands
git fetch origin master:tmp
git rebase tmp
git push origin HEAD:master
git branch -D tmp

```


* At very first step use `pip install -r requirements.txt` command to install all the dependencies.
* Command used to start the project `django-admin startproject ProjName or django-admin startproject ProjName .` 
* Now we will migrate and makemigrations of our project using cmd `python manage.py makemigrations & migrate`
* Use cmd `python manage.py createsuperuser` to create ur admin userid pass.[Note: Repeat the migrate step again and runserver]
* Applying `django-admin startapp feed` django-admin to create a new app.
* There we need to add the feed app name in settings installed app section.
* Feed consists view, urls, models, app, admin. 
* Now runserver and Checking the admin section pass the user id pass in it.
* Move to `models` files where we will make changes to see the post.
* In models added a class based Post.
* There now make views and urls for feed and til.
* If we check the views so we have home page inside that and url feed and lit contains that view module.
* Also need to change path in setting to redirect the templates html files in take places.

