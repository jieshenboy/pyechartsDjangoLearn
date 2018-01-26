# pyecharts + Django
这个是学习pyecharts模块，运用的后端是Django。

```
pip install Django
pip install pyecharts
#运行Django的时候需要将Django加入环境变量中，这样才可以使用Django
```
## Step1:新建一个django项目
$django-admin startproject myechartsite #创建一个django文件，文件名叫myechartsite

创建一个应用程序
```
$python manage.py startapp myfirstvis
```
在myechartsite/settings.py中注册应用程序
```
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'myfirstvis',#注册应用程序
]
```
