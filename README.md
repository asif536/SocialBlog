# Social Blog
This is Social Blog Website Made by Using Python Using django 1.9

### Dependencies

Make you sure your computer have installed following Dependencies.

```
Python 2.7.11

pip

vertualenv

```

### Setup to run

Extract zip file in your computer

Open terminal/cmd promt

Goto that Path

Example

```
cd ~/Destop/SocialBlog
```
Create a new virtualenv on that directory

```
virtualenv .
```

Activate Your Virtual Environment

for Linux
```
source bin/activate
```
for Windows

Goto Scripts directory type activate

```
cd Scripts/activate
```
Downloading requirements

```
pip install -r requirements.txt
```
It will install all requirements.

### Creating LocalHost

goto src directory example

```
cd /SocialBlog/src
```
Type following command  
```
python manage.py makemigrations

python manage.py migrate

python manage.py runserver
```

Open your browser and type

```
http://127.0.0.1:8000
```
Now website ready to Run.
