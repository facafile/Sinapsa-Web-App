This is a Web aplication developed by a group of 7 in college. 
The technologies used are 
![https://img.shields.io/badge/React-20232A?style=for-the-square&logo=react&logoColor=61DAFB](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![https://img.shields.io/badge/Spring-6DB33F?style=for-the-square&logo=spring&logoColor=white](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)


I was working on the backend of the app.

The app itself is a system for asking or receiving help for certain assignments we have for our college courses. 

When you register and login you can build your own notice for what you want and then other people can leave a comment wanting to help you or wanting help with that topic. 

There is a grading system implemented. One can only grade his helper if the help is offered. 

There is a ranking system for the best helpers.

You can only register if your mail domain is fer.hr but this can be changed easily in code.

The app is connected to a mail server and sends emails during registration, deletion of notices and when your notice gets a new comment.





We removed passwords and usernames for email clients and the database, so in order to run this code you need to put your own values for the attributes in question.

They are located in the application.properties file on the backend.



Frontend has proxy files that redirect it to a host render.com but this can be deleted to run locally. 

Testing for the classes is also included in the project.
