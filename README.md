JWT Authorization in Flask

``` bash
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt

# serve back-end at localhost:5000
FLASK_APP=run.py flask run
```


# user auth 
1> takes username and password and returns access token, 
2> stores in DB.
3> Logins the user w.r.t correct username and password else sends error.
4> Able refresh the access tokens updates User's Information
5> Logs out user


Endpoints

All of these endpoints should be written from a user's perspective.

    User Registration
    Login (token based) - should return a token, given valid credentials
    Logout - logs a user out
    Update a User's Information
    Delete a User

# Choosing Flask as it has modules of JWT and also used hsh for access tokens
# with more time can do sophisticated retieval and updates 


# Fender Digital Platform Engineering Challenge

## Description

Design and implement a RESTful web service to facilitate a user authentication system. The authentication mechanism should be *token based*. Requests and responses should be in **JSON**.

## Requirements

**Models**

The **User** model should have the following properties (at minimum):

1. name
2. email
3. password

You should determine what, *if any*, additional models you will need.

**Endpoints**

All of these endpoints should be written from a user's perspective.

1. **User** Registration
2. Login (*token based*) - should return a token, given *valid* credentials
3. Logout - logs a user out
4. Update a **User**'s Information
5. Delete a **User**

**README**

Please include:
- a readme file that explains your thinking
- how to setup and run the project
- if you chose to use a database, include instructions on how to set that up
- if you have tests, include instructions on how to run them
- a description of what enhancements you might make if you had more time.

**Additional Info**

- We expect this project to take a few hours to complete
- You can use Rails/Sinatra, Python, Go, node.js or shiny-new-framework X, as long as you tell us why you chose it and how it was a good fit for the challenge. 
- Feel free to use whichever database you'd like; we suggest Postgres. 
- Bonus points for security, specs, etc. 
- Do as little or as much as you like.

Please fork this repo and commit your code into that fork.  Show your work and process through those commits.

