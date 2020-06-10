# LifeQuest Coding Challenge

This coding challenge will involve a real-world situation and will test a number of things: 

* Ability to work with Git Repositories
* Ability to quickly get up to speed on an existing source base
* Angular Development Capabilities
* ASP.NET Web API Capabilities
* SQL Server

This exercise is purposefully vague.  Use your best judgements in coding and design decisions.  The actual result isn’t what is important here, but rather we are looking for you to show off some of your skills.  Feel free to show off as much as you want.   

Step 1) Clone the source code repository from GitHub (you should have been emailed an invite to the repository)  https://github.com/robertlair-lifequest/christiancharles-codechallenge

Step 2) Get Angular web application running.  The application resides in the folder “web”

Step 3) Add a new capability to the web application to manage companies.  (Use UI from existing template screens to generate a consistent look)  This should include the following: 

* Add entry in left menu titled “Companies” that will point to the Companies Listing Screen.  
* Add a List Screen. This screen will contain a grid of companies.  Each company listing will have an "Edit" button in the first column.  When you click on the edit button it will take you to the Company Edit Screen.  In addition, there will be a "Create New Company" button above the data grid.
* Add an Add/Edit Screen.  This screen should have input fields for with validation to submit changes to the company.  

The company object should have the following fields: 

* ID (int)
* Name (string)
* Address (string)
* City (string)
* State (string) - Optionally you can make this an int and have the state represented by a drop down
* Zip (string)

Step 4) Create an ASP.NET Web API to serve the company screens on the angular project.  Use a SQL Server Express to store the company information.  Be sure to generate a backup of your database (or export a script with schema AND data).  Be sure to add the data backup or scripts to a folder named “data” in the repository.  The web api should have the following: 

* Get a list of all companies
* Get details of a specific company by Id
* Submit changes a company by Id

Please keep a coding journal describing what you did and why.  Documentation on how to get your example running will be expected (the documentation is part of the coding challenge).  

Good luck!

