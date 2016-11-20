# Restaurant-menu-app
   An application that displays the restaurant menu items. The third party authorization is used(like fb,google plus). The registered users can edit and delete menu items that they have created. 
   
# sqlAlchamey
   The sqlAlchamey Object Relational Mapper is useful in associating the python classess with the database table.
   The tables are stored in the seperate file.It can be accessed inside our main program using the following command
      create_engine('sqlite:///databsename.db')
   
# Framework
   Flask python web frameowrk is used for developing this application. The template is very useful when the main application requests for sepcific url. The temples used here has .html extension and the values gets updated based on the function that calls this template.
   http://flask.pocoo.org/docs/0.11/
   
# Oauth
  The third party authentication is used. The request is sent to the server and the response from the server is stored in JSON file. The JSON file is used to check for valid users.
  Step 1:
  register app in the following sites
  ## facebook:
  https://developers.facebook.com/
  ## googleplus:
  https://console.developers.google.com/apis/api?project=maptest-140718
  
  Step 2:
  get the client id,secret and access_token
  Store them as .json files
  
# vagrant box 
  The vagrant VM is used here.It can be installed using the following link
  https://www.vagrantup.com/
  
  The vagrant box will be turned on by the following command
  Vagrant up
  
  The secured socket shell helps to interact with vm which can be done using the command
  Vagrant ssh
 
  The localhost server is used for running the application.Access it using,
  https://localhost:8080/
 
The database file should be run before running the main program inside vagrant:
The python will be already installed inside vagrant.so simply type the below command
      python databasename.py
The above command will load data's to the database.

The application will then run by the following command:
Simply type the command below to run the program.
     python projectname.py

  

    
