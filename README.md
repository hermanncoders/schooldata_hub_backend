# Hermanndata

WIP für REST API Backend unserer Daten

# Before production

- UserWarning: The 'sha256' password method is deprecated and will be removed in Werkzeug 3.0. Migrate to the 'scrypt' method.
- set .env and refactor
- Uncomment `def create_user()` in app.py (line 387 ff)
- Implement Log in database
- Setup swagger authentication properly
- Implement websocket or comment it out

# SETUP

https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-22-04

## WIKI to self

**Flask best practices:**
- https://python.plainenglish.io/flask-restful-apis-72e05f8d41fa
**Relationships & back_populates:**
https://stackoverflow.com/questions/51335298/concepts-of-backref-and-back-populate-in-sqlalchemy

**Swagger for flask:**
- https://stackoverflow.com/questions/62066474/python-flask-automatically-generated-swagger-openapi-3-0
- https://apispec.readthedocs.io/en/latest/index.html
- http://donofden.com/blog/2020/06/14/Python-Flask-automatically-generated-Swagger-3-0-openapi-Document

**Many to many delete orphans:**
- https://github.com/sqlalchemy/sqlalchemy/wiki/ManyToManyOrphan
- https://stackoverflow.com/questions/68355401/how-to-remove-sqlalchemy-many-to-many-orphans-from-database

**Complex routes:**
- https://hackersandslackers.com/flask-routes/

**Files upload:**
- https://stackoverflow.com/questions/19898283/folder-and-files-upload-with-flask
**Images:**

**Websocket:**
- https://www.donskytech.com/python-flask-websockets/?utm_content=cmp-true
- https://blog.miguelgrinberg.com/post/add-a-websocket-route-to-your-flask-2-x-application
- https://www.educba.com/flask-websocket/
- https://www.twilio.com/docs/voice/tutorials/consume-real-time-media-stream-using-websockets-python-and-flask
    
**SocketIO:**
- https://www.youtube.com/watch?v=FIBgDYA-Fas 
- https://stackoverflow.com/questions/32545634/flask-a-restful-api-and-socketio-server
- https://medium.com/flutter-community/flutter-integrating-socket-io-client-2a8f6e208810
- https://pub.dev/packages/socket_io_client/example
- https://flask-socketio.readthedocs.io/en/latest/getting_started.html
- https://stackoverflow.com/questions/57311552/flask-socket-io-onevent-not-handled-but-onmessage-works-fine
- https://dev.to/djsmk123/flutter-python-web-socket-ft-socket-io-part-1-3icf
- https://github.com/Djsmk123/web_socket_example_backend/blob/main/main.py
