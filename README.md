Pivotal Tracker Planning Poker Using Zero MQ
=========


INSTRUCTIONS TO GET SET UP
-------------------------

1. Install virtual environment ```pip install virtualenv``` or it could be ```easy_install virtualenv```
2. Create a virtual env called venv ```virtualenv venv``` or it could be ```python virtualenv.py venv```
3. Activate your venv by typing ```source venv/bin/activate```
4. Install requirements into your virutal environment ```pip install -r requirements.txt```
4a. If step 4 fails --- You may need to ```brew install libevent```  and ```pip install pyzmq gevent_zeromq```
6. Run the server ```python manage.py runserver```