# Hive-Hut

It is a Full-stack Social Media website that has authentication(login/signup) functionality, 
upon registration a user profile is created and the user is taken to the home page of the application.
JWT Authentication has been used to authenticate the user in this app.<br>
In the home page there is an option to post something (image or text), the image posted are stored in 
the local storage. Rest API is used to handle the posts and the users. 
<br>In the left side of the page, the user profile picture and cover picture is shown 
in a card and below that the followers list is shown(The other people who have registered).<br>
Upon going to "My Profile", user profile is shown where the user can fill in information about them
and they can also update/change their cover picture and profile picture.<br>
The app also supports dark and light mode.
Users can follow and unfollow other users and it will render across the entire app.


## Dependencies

[![dependency - Node.js](https://img.shields.io/static/v1?label=dependency&message=Node.js&color=%23F7E152)](https://nodejs.org/en/)  

[![library - React.js](https://img.shields.io/static/v1?label=library&message=React.js&color=%2352F7BA)](https://reactjs.org/)    

[![icons - react unicons](https://img.shields.io/static/v1?label=icons&message=react+unicons&color=%2352C2F7)](https://iconscout.com/icons?gclid=CjwKCAiAwc-dBhA7EiwAxPRylPC3t-9e5BD0qGYYpi6p8e1Ub8JHd18hqx4h0iwB_KswYTnXbAj2iRoCLboQAvD_BwE)      

[![language - javascript](https://img.shields.io/static/v1?label=language&message=javascript&color=%23EEF752)](https://www.javascript.com/)

[![modal - mantime-modal](https://img.shields.io/static/v1?label=modal&message=mantime-modal&color=%23F76F52)](https://mantine.dev/core/modal/)       

[![authentication - JWT](https://img.shields.io/static/v1?label=authentication&message=JWT&color=%23F7525B)](https://jwt.io/introduction)       

[![database - mongoDB](https://img.shields.io/static/v1?label=database&message=mongoDB&color=%23F7525B)](https://www.mongodb.com/home)        

[![API - Rest API](https://img.shields.io/static/v1?label=API&message=Rest+API&color=%237DCEA0)](https://restfulapi.net/)

[![Dependency - Express](https://img.shields.io/static/v1?label=Dependency&message=Express&color=%23F39C12)](https://expressjs.com/)

[![Library - Mongoose](https://img.shields.io/static/v1?label=Library&message=Mongoose&color=%233498DB+)](https://mongoosejs.com/)

[![Encryption - bcrypt](https://img.shields.io/static/v1?label=Encryption&message=bcrypt&color=%235DADE2)](https://www.npmjs.com/package/bcrypt)




## Demo

https://social-media-yqi8.onrender.com


### Sign up page - 

![Screenshot (75)](https://user-images.githubusercontent.com/64829176/210399419-9e7dd58d-955e-4121-aed5-14b062c7b045.png)


### Login Page - 

![Screenshot (76)](https://user-images.githubusercontent.com/64829176/210399512-3dc46f3d-a20f-4d74-b38f-6346f0aab141.png)


### Home Page - 

![Screenshot (69)](https://user-images.githubusercontent.com/64829176/210399756-8dc3d642-e40a-4abf-ae12-3a9dbf4ad68a.png)


### Profile Page - 

![Screenshot (72)](https://user-images.githubusercontent.com/64829176/210399895-6a915ace-0917-4407-9a97-146efa961c60.png)


### Share function - 

![Screenshot (71)](https://user-images.githubusercontent.com/64829176/210400002-e223f47a-733c-4906-80b6-bcf32fad3532.png)


### Information update -

![Screenshot (73)](https://user-images.githubusercontent.com/64829176/210400338-0b66ac47-2091-42bd-9502-3e80c8f7d087.png)


### Dark Mode - 

![Screenshot (74)](https://user-images.githubusercontent.com/64829176/210400615-c2396116-cdc7-4c61-9125-a325fc24dab8.png)



## Deployment

This project has been deployed using render.
For the separate files i.e. client and server, we make two different web services.
For server we use web site deployment and for client we use static site 
deployment.
We upload the .env variables to the site and we give access to the IP addresses in 
Mongo DB.








