 Info:
 Authentiacation using JWT token

 For Backend
 Step 1:
 Create virtual env

 * python3 -m pip install virtualenv
 * python3 -m virtualenv venv 
 * source ./venv/bin/activate

 Step 2:
 Install dependencies
 * pip install -r requirements.txt 

Step 3:
 Run make migration
 *  python manage.py makemigrations 

Step 4:
 Run migrate 
 *  python manage.py migrate

step 5: run (run in port 8000 (frontend cogiigured with port 8000))
* python manage.py runserver

_________________________

For forntend

Step 1:
    Install all packages

   * npm install
step 2:
    Run project
   * npm start