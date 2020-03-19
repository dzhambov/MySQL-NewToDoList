# _To Do List_

#### _A C# MVC application to track tasks by category._, _Mar. 18, 2020_

#### By _**Benjamin Thom, Hristo Dzhambov, Jonathan Carlos**_

## Description

_A program for a user to track tasks based on custom categories (such as Home, Work, etc)._

## Project Specifications

| Behavior | Input | Output |
|---|:---:|:---:|
|The program displays a welcome message "Welcome to the To Do List!" and two links for viewing categories "See all categories" and viewing items "See all items"|User enters the following url: http://localhost:5000| Welcome Message: "Welcome to the To Do List!"|
|User clicks on "See all categories" or "See all items" and is routed to the corresponding view with options to add new category or item|User clicks on link and the programs displays currently added items or categories|Catagories: "Home" Items: "Walk the dog"|
|A user clicks the "add new category/item" link and is routed to a new category/item view where they can insert category/item details. Once the user inputs the details, the user can hit submit and will be routed to the categories/items view|User clicks on selected "add new" link and inserts category/items details, and hits submit|"Add a new category/task", Description: "Home"/"Walk the dog", click "Add new category/task" button|

## Setup/Installation Requirements

_In Terminal:_

* Navigate to where you want this application to be saved, i.e.:
```cd desktop```
* Clone the file from GitHub with HTTPS
```git clone https://github.com/jonathancarlos21/mySQL-to-do-listn.git```
* Open file in your preferred text editor
* On Mac: ```open -a {your text editor} mySQL-to-do-list```
* On Windows: ```mySQL-to-do-list```

_Download Manually:_

* Navigate to https://github.com/jonathancarlos21/mySQL-to-do-listn.
* Click the green "Clone or Download" button.
* Click "Download ZIP".
* Click downloaded file to unzip.
* Open folder called "mySQL-to-do-list".

_Note For Editors:_ 
* Download the .NET Core SDK [Software Development Kit](https://dotnet.microsoft.com/download)
* Open the .Net Core SDK file and install
* To confirm installation was successful, run the ```$ dotnet --version``` command in your terminal

* Install dotnet script, run the ```$ dotnet tool install -g dotnet-script``` command in your terminal
* Restart your terminal to complete installation, and run the ```$ dotnet run``` command to run application within your terminal - Note: To exit, simply press ```Ctrl + C```

## Known Bugs

_No known bugs at this time._

## Support and contact details

_Have a bug or an issue with this application? [Open a new issue](https://github.com/jonathancarlos21/mySQL-to-do-listn/issues) here on GitHub._

## Technologies Used

* _Git 2.23.0_
* _C# language_
* _.NET Core 2.2.106_
* _dotnet script 0.50.1_
* _VS Code 1.43.1_
* _Model-View-Controller(MVC) framework_
* _Creat, Read, Update, Delete(CRUD) functionality_
* _MySQL_
* _MySQL Workbench_
* _Entity Framework Core_
* _Language-Integrated Query(LINQ)_
* _ASP.NET Razor_

### License

*This webpage is licensed under the MIT license.*

Copyright (c) 2020 **_Benjamin Thom, Hristo Dzhambov, Jonathan Carlos_**