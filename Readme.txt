Hello,
This is a basic blog application, created in Angular with WebApi
In this application we have below funcationality
1-Login
2-Signup
3-User panel(create new blog and modify old one)
4-Admin Panel(Manage application users)
-----------------------------------------------
Created by below Tech.
Angular CLI
Web API (.net 4.6.1)
Materialize CSS (front end framework)
----------------------------------------------
Required Software and installation command 
1-VS Code & Visual Studio 
2-Install node.js
  URL:https://nodejs.org/en/
      node versio 8.11.1
3-open comand prompt and run the below comand to angular CLI
  npm install -g @angular/cli\
----------------------------------------------
How to create DB
please run the attached script(seed sql script) in the DB it will create the DB.
----------------------------------------------
How to run the application?
In the Zip file we two diffrent applicaion one web api and other web application.
1-MyBlogApplication
  a-open this the applicaion in the VS code 
  b-open the MyBlogApplication folder in the terminal(right click and open in terminal)
  c-run comand "npm install"
    example: 
    MyBlogApplication> npm install
  d- after packages installation run the below comand in the terminal
      ng serve --open
      it will open the application in the default browser.     
2-WebApi(open in the Visual studio)
  a-Update the nuget packages and build the application 
  c-please check the application port, it should be 6830.
  d-change the Db connection string
  -----------------------------------------------
Default URL
http://localhost:4200/index
---------------------------------------------

