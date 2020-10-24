# Instapic is a Picture Sharing App built using Python Web framework Django

## Getting Started

-Install the prerequisites
### Prerequisites

You can install the Prerequisites by running the command:
```
pip install -r requirements.txt
```

```
asgiref==3.3.0
certifi==2020.6.20
Django==3.0.3
Pillow==8.0.0
pytz==2020.1
sqlparse==0.4.1
wincertstore==0.2

```
-Run the server

admin:
demo
password:
demo1234

use the following urls to see the features
http://127.0.0.1:8000/user/signup/-->signup is displayed,once you singup it is redirected to login page
http://127.0.0.1:8000/user/login/-->once you login with proper credentials, it redirects to your home page or post page
http://127.0.0.1:8000/post/-->you have options to see your profile, under settings you can logout, if you are following any other user their posts will be displayed (with latest posts first), you can click on the post and it will redirect to post detail page where you can like or save the post.
http://127.0.0.1:8000/user/profile/edit-->you can edit your profile
http://127.0.0.1:8000/(username ex demo in the above example)/-->you can see your posts and saved posts, you can see the count of users following you, count of users whom you follow, the number of posts made by you and also the number of likes for your post

http://127.0.0.1:8000/post/newpost/--->you can create a new post and it will be appeared as feed in the users account who are following you

http://127.0.0.1:8000/(name of other user)/-->it will display the other user profile and you can follow or unfollow him/her
