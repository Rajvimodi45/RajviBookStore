Assignment2:- Bookstore

Phase #1
---------------------------------------------------------------------------------

		2021/11/03
		----------

			2:00 - Create new ASP.NET core(MVC) web application of name RajviBookStore
			2:00 - configuired the project
			2:03 - Run the project
			2:04 - create the github repository named Assignment2 and push the assignment2 to my github.

			Oh It successfully ran.

		5 Minits

		2021/11/10
		----------

			2:08 - Go the bootswatch.com
			2:08 - and selected the theme "SLATE"
			2:09 - replaced the bootstrap.css file of the theme to current css file located in wwwroot folder.
			2:10 - also replaced the main site.css file to the site.css file in the assignment2 folder in blackboard.
			2:15 - changed file name from bootstrap.min.css to bootstrap.css
			2:20 - Changed the nav class from navbar-light to navbar dark and bg-white to bgprimary
			2:30 - add extrea properties to footer class text-white-50 and bg primary
			2:45 - run the project  

		theme is successfully applied.

		40 Minits

		2021/11/13
		----------
			2:15 - In _Layout.cshtml, added the additional stylesheets and scripts from the file CSS_JS.txt file.
			2:17 - Adding dropdown in navbar 
			2:18 - run the project
			2:20 - Adding three new project in application
			2:20 - three new projects - RajviBooks.DataAccess, RajviBooks.Models, RajvitaBooks.Utility
			2:21 - copied data folder and pasted into new project .DataAccess 
			2:21 - deleted the original folder
			2:23 - Installed the packages: Microsoft.EntityFrameworkCore.Relational and Microsoft.EntityFrameworkCore.Sqlserver
			2:26 - Deleted the migration folder
			3:27 - Installed the Identity.EntityFrameworkCore
			3:28 - In ApplicationDbContext.cs, changed the namespace to RajviBookStore.DataAccess.Data
			3:29 - Deleted all the Class1.cs files from .DataAccess, .Models and .Utility project
			3:35 - Moved the models folder into RajviBooks.Models
			3:36 - In main project, Added the two project references - .DataAccess and .Models
			3:38 - Changed the model folder name to Viewmodel
			3:39 - run the project

		1 Hour and 30 Minits

2021/11/14
----------

		4:42 - solve the error by using.RajviBookStore.DataAccess.Data
		4:43 - removed the using.RajviBookStore.Data
		4:50- Corrected default reference @model RajviBookStore.Models.ViewModels.ErrorViewModel
		4:52 - run the project

		it successfully run!


		5:50- Added new class file named SD.cs in utility project
		5:52 - added project reference in the main project
		5:54 - added Models and Utility reference to .DataAccess project.
		5:57 - Add a new area named Customer
		5:59 - Deleted data and models folder from Areas and moved the HomeController.cs file to the Area>Customer>Controller
		5:08 - run the application

		run successfully but different webpage loaded

		6:09 - copied the _ViewStart and ViewImport to customer area
		6:10 - added the new path to _ViewStart.cshtml
		6:11 - run the application

		Yeah after solving the error it  successfully run

2 Hours

Phase #2
----------------------------------------------------------------------------------------

	2021/15/1
	---------

		3:15 - Added a new area named Admin
		3:16 - Deleted data and models folder from Admin area and copied _ViewStart and ViewImport to admin area
		3:19 - Deleted the controller folder
		3:20 - run the application

		Successfully build.

		5:00 - build the application and it successfully build
		5:01 - open the Nuget package manager console and run the command add-migration AddDefaultIdentityMigration 
		5:06 - default project is RajviBookStore so it showing error 
		5:06 - select the RajviBooks.DataAccess
		5:07 - run the command add-migration AddDefaultIdentityMigration

		5:20 - to update the database run the command - update-database
		5:20 - successfully build 
		5:21 - checked the updated table in SQL server object explorer
		5:21 - run the project

		run successfully.

		5:25 - created the new class file in .Models project.
		5:26 - modified the code.
		5:30 - added the migration via console by command - add-migration AddCategoryToDb

		5:35 - modify the applicationDbContext.cs file
		5:38 - re-run the command - add-migration AddCategoryToDb
		5:40 - edited the migrated file 20211115022846_AddCategoryToDb and checked the updated database 

		database is updated successfully......

	2 Hours

	2021/11/19
	----------

		6:00 - In RajviBooks.DataAccess, created new folder name Repository
		6:00 - In Repository folder, created new IRepository folder for interface
		6:02 - In  IRepository folder, created the new interface and named it as  IRepository.cs
		6:04 - Modified  IRepository.cs to perfoem CRUD operations.
		6:06 - In Repository folder, created new class named  Repository.cs
		6:06 - modified it but got some errors 
		6:08 - by implementing interface in potential error fixes my error got solved.
		6:10 - modifiedn the code to create the constructors and depedency injection

	10 Minits

	2021/11/20
	----------
		6:11 - copied the Repository.cs file from assignment2 folder in blackboard
		6:12 - created the class CategoryRepository.cs in  Repository
		6:13 - created the interface ICategoryRepository in IRepository
		6:15 - modified the CategoryRepository.cs
		6:30 - modified the CategoryRepository.cs
		6:32 - got some error but fixed it by using statement
		6:33 - pushed all the changes to github
		7:00 - added the new interface in IRepository folder named ISP_Call.cs
		7:02 - included the code and installed the Dapper NuGet package

	20 Minits

	2021/11/22
	----------
		6:03 - got some errors but solved it using potential error fixes
		6:10 - Added new class to Repository folder named SP_call
		7:13 - modified the SP_call
		8:05 - got some errors
		12:00 - reloved the errors and puch code in git

	4 hours

	2021/11/28
	----------

		9:05 - try to resolved the git errors
		10:09 - commit whole project over git and check it is working or not
		10:15 - clone the project and check the fuctionality

		its working properly

	1 Hour

Phase #3
---------------------------------------------------------------------------------

	2021/11/30
	----------

		1:05 - create category repository
		1:09 - Change in UnitofWork.cs 
		1:20 - create migration and update database
		1:30 - migration successfully created
		1:50 - create controller and view for category 
		2:30 - Faced some errors and try to resolve it
		3:40 - resolved errors and checked 

		run successfully.

	3 Hours

	2021/12/1
	---------

	5:25 - created the new class file in .Models project.
	5:26 - modified the code.
	5:35 - modify the applicationDbContext.cs file
	5:38 - re-run the command - add-migration AddCoverTypeToDb

	and yeahhhh database is updated successfully......

	6:00 - In RajviBooks.DataAccess, created new folder name Repository
	6:00 - In Repository folder, created new IRepository folder for interface
	6:02 - In  IRepository folder, created the new interface and named it as  IRepository.cs
	6:04 - Modified  IRepository.cs to perfoem CRUD operations.
	6:06 - In Repository folder, created new class named  Repository.cs
	6:06 - modified it but got some errors 
	6:08 - by implementing interface in potential error fixes my error got solved.
	6:10 - modifiedn the code to create the constructors and depedency injection
	6:12 - created the class CoverTypeRepository.cs in  Repository
	6:13 - created the interface ICoverTypeRepository in IRepository
	6:15 - modified the CoverTypeRepository.cs
	6:30 - modified the CoverTypeRepository.cs
	6:32 - got some error but fixed it by using statement
	6:33 - pushed all the changes to github

	13:30 - create cover type repository
	13:40 - Change in UnitofWork.cs 
	13:55 - create migration and update database
	13:10 - migration successfully created
	13:25 - create controller and view for cover type
	13:50 - Faced some errors and try to resolve it
	14:10 - resolved errors and checked 

	oh it ran successfully.

	7 Hours

Phase #4
---------------------------------------------------------------------------------

	2021/12/2
	---------

		7:00 - create cover type Products
		7:10 - In Repository folder, created new IRepository folder for interface
		7:30 - In  IRepository folder, created the new interface and named it as  IRepository.cs
		7:40 - Modified  IRepository.cs to perfoem CRUD operations.
		7:45 - Change in UnitofWork.cs 
		7:55 - create migration and update database
		8:08 - by implementing interface in potential error fixes my error got solved.
		8:10 - modifiedn the code to create the constructors and depedency injection
		8:12 - created the class CoverTypeRepository.cs in  Repository
		8:13 - created the interface ICoverTypeRepository in IRepository
		8:15 - modified the CoverTypeRepository.cs
		8:30 - modified the CoverTypeRepository.cs
		8:32 - got some error but fixed it by using statement
		9:20 -  migration successfully created
		9:30 - create controller and view for cover type
		10:15 - Faced some errors and try to resolve it
		11:00 - resolved errors and checked

	4 Hours


 

