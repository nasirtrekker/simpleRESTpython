#Nasir Uddin

The rest service uses web.py to create a server and it will have two URLs, one for accessing all users and one for accessing individual users:

http://localhost:8080/users
http://localhost:8080/users/{id}
First you will want to install web.py if you don't have it already.

sudo easy_install web.py
-Example of simplest REST web service with python
-To run your service, simply run:

python rest.py
- This creates a web server on port 8080 to serve up the requests. This service returns JSON responses, you can use any of the following URLs to see an example:

- http://localhost:8080/users
- http://localhost:8080/users/1
- http://localhost:8080/users/2
- http://localhost:8080/users/3
