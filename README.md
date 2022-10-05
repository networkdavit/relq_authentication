# relq_authentication

How to test

# git clone https://github.com/networkdavit/relq_authentication.git
# cd relq_relq_authentication
# npm install
# nodemon main.js


--------------------------

Make a get request 
http://localhost:3000

response- Unauthorized

Make a post request to register
http://localhost:3000/register

body
{
    "username": "test", 
    "password": "test123"
}

response - User created

Make a post request to login
http://localhost:3000/login

{
    "username": "test", 
    "password": "test123"
}

repsponse - jwt_token: "somerandomtokenhere"

In postman, go to Authorization tab, click on "Bearer Token" type, and paste your JWT token
Make a get request 
http://localhost:3000

response - Hello World


