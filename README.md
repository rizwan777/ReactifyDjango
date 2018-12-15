# ReactifyDjango
This Boilerplate is the setup for the React and Django combination with the django-restful apis for the web apps development..

# Front End
For frontend Development 
  1. check the node is installed or not in your working system
  2. then check for the react instalation. if not then you find it on docs about the installation.
     # this library which support the react based front end develpoment "create-react-app"
  3. after that you need to install the the middle level libraries for forntend routings 
     # this library is the "react-router-dom"
  4. after that interaction with the backend server by installing the 
    # "axios" or "fetch" library 
# For backend Development
  1. make sure about the virtualenv or pip environment is active and check for
    # django, django-rest-framework,etc. is installed already. if not then install it
  2. After the Project is built with the functionality then find out the requirements of the project by built an API's interaction.
      install external library for frontend interaction with the api by installing 
      # "Django-cross-headers" and also grant permission for it.
      # (note:: after developing project and apis you need to add some permission for externel interaction with the project by giving permission in setting.py file. {django-restframework , django-corss-headers})
   
   # note: #
   # 1. for better UI add more library in the react development "antd"
   # 2. you can build the project in main django project for easy to find and used for frontend development
   # 3. after both works fine then run backend server to check the output.
   # 4. whatever the changes are you are going for that time you need to see the result with the data from apis.
        cmd : "npm run build"
   # -> it will save the changes and bind it with the main backend project.
