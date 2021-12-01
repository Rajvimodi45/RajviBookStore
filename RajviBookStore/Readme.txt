Assignment2:- Bookstore

2021/11/03 2:00 - Create new ASP.NET core(MVC) web application of name RajviBookStore
2021/11/03 2:00 - configuired the project
2021/11/03 2:03 - Run the project
2021/11/03 2:04 - create the github repository named Assignment2 and push the assignment2 to my github.

Oh It successfully ran.

2021/11/10 2:08 - Go the bootswatch.com
2021/11/10 2:08 - and selected the theme "SLATE"
2021/11/10 2:09 - replaced the bootstrap.css file of the theme to current css file located in wwwroot folder.
2021/11/10 2:10 - also replaced the main site.css file to the site.css file in the assignment2 folder in blackboard.
2021/11/13 2:11 - changed file name from bootstrap.min.css to bootstrap.css
2021/11/13 2:11 - Changed the nav class from navbar-light to navbar dark and bg-white to bgprimary
2021/11/13 2:12 - add extrea properties to footer class text-white-50 and bg primary
2021/11/13 2:13 - run the project  

theme is successfully applied.

2021/11/13 2:15 - In _Layout.cshtml, added the additional stylesheets and scripts from the file CSS_JS.txt file.
2021/11/13 2:17 - Adding dropdown in navbar 
2021/11/13 2:18 - run the project
2021/11/13 2:20 - Adding three new project in application
2021/11/13 2:20 - three new projects - RajviBooks.DataAccess, RajviBooks.Models, RajvitaBooks.Utility
2021/11/13 2:21 - copied data folder and pasted into new project .DataAccess 
2021/11/13 2:21 - deleted the original folder
2021/11/13 2:23 - Installed the packages: Microsoft.EntityFrameworkCore.Relational and Microsoft.EntityFrameworkCore.Sqlserver
2021/11/13 2:26 - Deleted the migration folder
2021/11/13 2:27 - Installed the Identity.EntityFrameworkCore
2021/11/13 2:28 - In ApplicationDbContext.cs, changed the namespace to RajviBookStore.DataAccess.Data
2021/11/13 2:29 - Deleted all the Class1.cs files from .DataAccess, .Models and .Utility project
2021/11/13 2:35 - Moved the models folder into RajviBooks.Models
2021/11/13 2:36 - In main project, Added the two project references - .DataAccess and .Models
2021/11/13 2:38 - Changed the model folder name to Viewmodel
2021/11/13 2:39 - run the project


2021/11/13 2:42 - solve the error by using.RajviBookStore.DataAccess.Data
2021/11/13 2:43 - removed the using.RajviBookStore.Data
2021/11/13 2:43- Corrected default reference @model RajviBookStore.Models.ViewModels.ErrorViewModel
2021/11/13 2:44 - run the project

it successfully run!

2021/11/13 2:50- Added new class file named SD.cs in utility project
2021/11/13 2:52 - added project reference in the main project
2021/11/13 2:54 - added Models and Utility reference to .DataAccess project.
2021/11/13 2:57 - Add a new area named Customer
2021/11/13 2:59 - Deleted data and models folder from Areas and moved the HomeController.cs file to the Area>Customer>Controller
2021/11/13 3:08 - run the application

run successfully but different webpage loaded

2021/11/13 3:09 - copied the _ViewStart and ViewImport to customer area
2021/11/13 3:10 - added the new path to _ViewStart.cshtml
2021/11/13 3:11 - run the application

Yeah after solving the error it  successfully run

2021/11/13 3:15 - Added a new area named Admin
2021/11/13 3:16 - Deleted data and models folder from Admin area and copied _ViewStart and ViewImport to admin area
2021/11/13 3:19 - Deleted the controller folder
2021/11/13 3:20 - run the application

Successfully build.

2021/11/13 5:00 - build the application and it successfully build
2021/11/13 5:01 - open the Nuget package manager console and run the command add-migration AddDefaultIdentityMigration 
2021/11/13 5:06 - default project is RajviBookStore so it showing error 
2021/11/13 5:06 - select the RajviBooks.DataAccess
2021/11/13 5:07 - run the command add-migration AddDefaultIdentityMigration
my migration folder name is :- 20211115040815_AddDefaultIdentityMigration
2021/11/13 5:20 - to update the database run the command - update-database
2021/11/13 5:20 - successfully build 
2021/11/13 5:21 - checked the updated table in SQL server object explorer
2021/11/13 5:21 - run the project

run successfully.

2021/11/14 5:25 - created the new class file in .Models project.
2021/11/14 5:26 - modified the code.
2021/11/14 5:30 - added the migration via console by command - add-migration AddCategoryToDb
my migration folder name is :- 20211115050046_AddCategoryToDb
2021/11/14 5:35 - modify the applicationDbContext.cs file
2021/11/14 5:38 - re-run the command - add-migration AddCategoryToDb
2021/11/14 5:40 - edited the migrated file 20211115022846_AddCategoryToDb and checked the updated database 

database is updated successfully......

2021/11/19 6:00 - In RajviBooks.DataAccess, created new folder name Repository
2021/11/19 6:00 - In Repository folder, created new IRepository folder for interface
2021/11/19 6:02 - In  IRepository folder, created the new interface and named it as  IRepository.cs
2021/11/19 6:04 - Modified  IRepository.cs to perfoem CRUD operations.
2021/11/19 6:06 - In Repository folder, created new class named  Repository.cs
2021/11/19 6:06 - modified it but got some errors 
2021/11/19 6:08 - by implementing interface in potential error fixes my error got solved.
2021/11/19 6:10 - modifiedn the code to create the constructors and depedency injection
2021/11/20 6:11 - copied the Repository.cs file from assignment2 folder in blackboard
2021/11/20 6:12 - created the class CategoryRepository.cs in  Repository
2021/11/20 6:13 - created the interface ICategoryRepository in IRepository
2021/11/20 6:15 - modified the CategoryRepository.cs
2021/11/20 6:30 - modified the CategoryRepository.cs
2021/11/20 6:32 - got some error but fixed it by using statement
2021/11/20 6:33 - pushed all the changes to github
2021/11/20 7:00 - added the new interface in IRepository folder named ISP_Call.cs
2021/11/20 7:02 - included the code and installed the Dapper NuGet package
2021/11/22 7:03 - got some errors but solved it using potential error fixes
2021/11/22 7:10 - Added new class to Repository folder named SP_call
2021/11/22 7:13 - modified the SP_call
2021/11/22 7:05 - got some errors
2021/11/22 12:00 - reloved the errors and puch code in git

 

