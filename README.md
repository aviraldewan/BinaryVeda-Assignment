# BinaryVeda-Assignment

NOTE- I am using Thunder Client (VS Code Extension) for making GET and POST Requests

# Register API
https://fair-plum-worm-cuff.cyclic.app/register

Objective- To register a new user by using above API in our MongoDB Atlas DataBase.

It accepts all of the following payloads:-
"name": <ENTER NAME HERE>
"age": <ENTER AGE HERE>
"email": <ENTER EMAIL HERE>
"phone": <ENTER PHONE NUMBER HERE>
"password": <ENTER PASSWORD HERE>

*Enter information without angular brackets

METHOD- POST

INPUT-
{
  "name": "test5",
  "age": 3,
  "email": "test5@test.com",
  "phone": "1382985672",
  "password": "test"
}

OUTPUT- 
Sign Up Successful!

IMAGE-
![image](https://user-images.githubusercontent.com/69675094/209469842-9174a79a-4d3f-4823-b008-9b7bc6d27c86.png)

# Login API
https://fair-plum-worm-cuff.cyclic.app/login

Objective- To allow the user to log-into our application

It accepts all of the following payloads:-
"email": <ENTER EMAIL HERE>
"password": <ENTER PASSWORD HERE>

*Enter information without angular brackets

METHOD- POST

INPUT-
{
  "email": "test5@test.com",
  "password": "test"
}

OUTPUT- 
Name: test5, Age: 3, Email: test5@test.com, Phone: 1382985672

IMAGE-
![image](https://user-images.githubusercontent.com/69675094/209469999-6bc39aa9-6acf-4acf-b865-1dc2a2735980.png)


# Logout API
https://fair-plum-worm-cuff.cyclic.app/logout

Objective- To allow the user to log-out from our application

It doesn't require any payloads

*It is only applicable for logged-in users

METHOD- GET

INPUT-
{

}

OUTPUT- 
Logged Out

IMAGE-
![image](https://user-images.githubusercontent.com/69675094/209470093-d1330933-2f1a-4878-9b61-8f667e9c949c.png)




Thanks for viewing and please share feedback for improvement!
