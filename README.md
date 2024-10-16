Clone the repo with

git clone https://github.com/SkyCascade/SkyLearn.git

Create and activate a python virtual environment

pip install -r requirements.txt

Create .env file inside the root directory
(env file daal raha hu, usme apna email id smtp se daalke naya app banaake password change kr dena)
I guess postgress ki zarurat nai hai
Make sure teko emails aa rahe hai login id aur password ke, ek baar ye sab setup ho jaye meko call krna for how to login vagera.

Jo deplot krega usme mera Email account daalna , toh yahi project deplot krna, credentials change mat krna.

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver

Last but not least, go to this address http://127.0.0.1:8000
