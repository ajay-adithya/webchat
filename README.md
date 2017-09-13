# webchat

A simple real time chat application using node.js and socket.io library deployed on heroku. Gravatar library is used to provide default avatars for users based on the email address. A private chat room which allows two people to communicat in real time. 

Deployment instructions in Heroku
 1)Donwload heroku CLI
 2)push all the local code to github, use .gitignore file to ignore node_modules directory
 3)make sure all the external references are made using HTTPS protocol since heroku serves via HTTPS
 4)cd root folder of the app
 5)heroku login, enter the credentials
 6)heroku create, to create a deployment space and associated git repo in heroku
 7)git push heroku master, all the code files are pushed to git of heroku and it is hence deployed
 8)heroku open
 
 Deployment URL:
  https://salty-ocean-19184.herokuapp.com/
