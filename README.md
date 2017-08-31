# Social Blog
This is Social Blog Website Made by Using Python Using django 1.9


## Getting Started

Just Click on clone or download button and download the repo and extract it.

### Prerequisites

Make you sure your computer have installed following Prerequisites.

```
Python 2.7.11

pip

vertualenv

```

### Installing

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
Downloading requirements file

```
pip install -r requirements.txt
```
It will install all requirements file 

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
https://127.0.0.1:8000
```
Now website ready to Run.
