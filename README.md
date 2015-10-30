TO RUN:

#Must have virtualenv set up
#run this in BMT folder:
virtualenv env

env/bin/pip install flask
env/bin/pip install flask-sqlalchemy
env/bin/pip install flask-wtf


#running the app
./env/bin/python run.py

#to see in action
http://0.0.0.0:8080/auth/signin
