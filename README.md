# Issue_Tracker
This Node.js and EJS application allows users to track issues and bugs for different projects. The application is designed with a user-friendly interface and provides various features to manage projects and their associated issues.

# Features
**1. Home Page**

    * Show a list of projects.
    
    * Provide a button to create a new project (new projects will appear in the project list).

**2. Create Project Page**

    Accept the following fields to create a project:
    
    * Name:
    
    * Description:
    
    * Author:

**3. Project Detail Page**

    * When the user clicks on a project in the home page, redirect the user to this page showing bugs related to the selected project.
    
    * Allow users to perform the following actions on this page:
    
        * Filter by multiple labels simultaneously.
        
        * Filter by author.
        
        * Search by title and description.

        * Create a new issue for the project.
        
**4. Create Issue Page**

    * Users should be able to create an issue for a project.
    
    * Accept the following fields to create an issue:
    
        * Title
        
        * Description
        
        * Labels (multiple labels can be added; show existing labels in a dropdown as the user types)
        
        * Author

# Project Setup
**1.Clone the repository**

    * git clone https://github.com/your-username/issue-tracker-frontend.git
    
    * cd issue-tracker-frontend

  **2.Install dependencies**

      * npm install

  **3.Run the starter file**
  
      * node server
      
  **4.Open localhost with the specified port in browser**

# Technologies Used

  * Node.js

  * EJS (Embedded JavaScript)
    
  * MongoDB

