# Task_Signup
 **Login page**
 
With the help of react,node,express and Mongodb created the fromt end an backend for the application since this is a signup page all the responses are supposed to be stored in the databse and thus I have used the post function for it the Mongo database was workin fine before the integration of the frontend but after the integration it ius returning an empty json object '{ }' like this.
 
 I have attached the Screenshots of the issue I have been facing.


## File structure and composition

### Backend
The application listen in the server.js file -> Task_Signup/signupbackend/server.js file and the folder contains the model(Task_Signup/signupbackend/models/) and routes(Task_Signup/signupbackend/routes/) schema in it.

### Frontend
The application integration is done in the App.jsx file -> Task_Signup/src/App.jsx.

The UI page ![Screenshot (556)](https://user-images.githubusercontent.com/40709301/104700268-e748ea80-5739-11eb-8d69-8d4a48bebf7b.png)

The major issue the post request is returning { } ![Screenshot (554)](https://user-images.githubusercontent.com/40709301/104701558-39d6d680-573b-11eb-935e-8f81697d50e2.png)

Tried the same thing with Resct client in visual studio it gave the same error![Screenshot (557)](https://user-images.githubusercontent.com/40709301/104702050-7aceeb00-573b-11eb-9e96-6b7876f593f5.png)

The frontend application is running smoothly ![Screenshot (558)](https://user-images.githubusercontent.com/40709301/104702273-c4b7d100-573b-11eb-9bf5-d38ff974afcb.png)
