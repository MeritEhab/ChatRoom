# chatRoom
A simple chat application that enables user to send and receive messages in realtime  

### Installation

Create a virtualenv for the project, and run:

```pip install -r requirements.txt```

Make sure Redis is running locally as the settings are configured to point to ```localhost```, port 6379, but you can change this in the ```CHANNEL_LAYERS``` setting ```in settings.py```.

Run python ```manage.py migrate```

To make an account run 
```python manage.py createsuperuser```

Then run ```python manage.py runserver```

You can deal with the users module through this links 

http://localhost:8000/rest-auth/registration/

http://localhost:8000/rest-auth/login

If you would like to run tests run 
```python manage.py test ```

To start chatting use this link:
http://localhost:8000/home

Click on the user you would like to chat with and start chatting  


