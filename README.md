Garold and Hian Blogs Documentation
Created By: Hian and Garold

Project Overview
  Garold and Hian Blogs (GH Blogs) attempts to create a fully 
  functioning MERN stack blog site with full CRUD capabilities. It features a login and registration page with full authentication,
  as well as the ability to post new blogs, see the total blogs, as well as editing and deletion.
  
Tech Used

  MongoDB - For database management
  
  Express - Backend framework
  
  React - Frontend module
  
  Node - JavaScript backend capabilities
  
  Git - Version control and collaboration
  
  npm - Package manager
  
  
Setup Instructions

	1. > git clone https://github.com/asharu734/csdc-final-project-real.git
 
	2. Open Visual Studio Code, open project
 
	3. Create terminal
 
	4. > yarn start
 
Code Explanation
  Frontend
    App.js connects all the modules and sets the main elements of the app. There were also props and the pages directory 
    which stores modular parts of the site. The main page and other modules are decorated with the App.css and index.css
  Backend
    The main file is index.js which contains the dependencies of the app. The database connection is also setup here, as
    well as middleware. Routes such as /register and /login are placed here and lastly, the server is set to listen on port 4000. Aside from that, the models directory has two modules that handle storing blogs and users.
