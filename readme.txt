# RaviBookStore
02-11-2021

07:00:Start to review the ppt from first to end for just review.
07:15: Read completly, and open visual and read the content in the blackbord.
07:22: create project repository properly, and strat on Git Hub.
07:24:  strat and change stratup file.

07:28:Review the ppt with visual studio that everthing okay
07:30:Run the code and that works properly.

07:35: Find some them in bootswatch.com
07:38: Got the theam which attract my eyes that is Darkly.
07:42: change Bootstrap file from lib

07:48:remove all text-dark and also complte footer side:
07:51:Run the project and that work properly
07:55: Check all 3rd party tools for information and take break for 10 min

08:05: change all given links 
08:10:I got and change all links
08:15: add dropdown menu but that not going to work i also check on the google and try different things but not work according to the given method
08:18 I implement this and take break

03-11-2021

12:00: Strat to add three class library.
12:10: Copy the Data folder to .Data Access and afraid to delete the origanl one.
12:30: complte the installation of frameWork and delete migration folder.
12:45: completed the changing in namespace;
12:50: Run the project it will work after changing the namespace;
01:00: Strat Add project reference and chnage the namespace
01:20: I was finding the error that where i make mistake after i desided to do steps again and i got sucess.
01:35: I realize that i mke a mistake in using statement id AddContext.
01:40: I got that this type of error will come by default that waste of time for me that i forget this kind of error
01:45: Add utility and customer area like move the controllerarea, explicitly define and all done take break 10 min;
01:48: change the viewport place and upadate github.
01:58: Completed the Whole project.


14-11-2021

05:30: Open the assignment 2 and review whole content folder.
06:00: Review the assignment 2 ppt
06:15: Strart by reviwing the appsetting.json file and update the databse.
06:18: Use the NuGet Package Manager Console to add the migration 
06:28: I added migration  ------- 20211115023639_AddDefaultIdentityMigration
06:35:  Review the updated database in the SQL Server Object Explorer.
06:38: Check for errors, run the application no error found
06:42: Add a new table to the DB by creating a Category model and push it to the DB
06:45: Add a new class file to the .Models project and modify
06:48: Add the migration via the PM Console ------ 20211115024626_AddCategoryToDb
06:50: Update this and note the added using statement
06:55: Update the database, confirm the new Categories table via the SQL SOE and push commits to GitHub

Break one and half hours

08:00: At the first sep i added new folder name Respository and sub folder named Irepository.
08:03: Change the header files requied code.
08:08: Implement the class that implement the repository.
08:15: I used using statement to resolve the issue and ceck the potencial fixes.
08:20: Create repository.ca and Irepository.cs and create a constructor using code given in assignment 2.
08:25: Modify so it can be used on the Category class to do all the CRUD operations 
08:28: Implement the class that implements the repository
08:32: Include the using statement
08:35: View the potential fixes and ???implement interface
08:40: Create individual repos for category and all potential models to be added which are CategoryRepository.cs, ICategoryRepository.cs
08:45: Modify CategoryRepository 
08:55: Modify ICategoryRepository interface
08:59: Review and modify the error now in CategoryRepository.cs 
09:15: Build, fix any error and push commits to GitHub

take Break

09:55: Implement a stored procedure repository and map multiple repositories in a Unit of Work
10:05: Add a new interface in the IRepository folder - ISP_Call.cs that extends IDisposable
10:15: Add a new class (SP_Call.cs) in the Repository folder
10:18: implement the ISP_Call interface
10:20: Add a connection to the database, note the additional using statements
10:22: Update the implementation of the ISP_Call interface
10:28: Now add the wrapper for Unit of Work
10:32: Add a new interface (IUnitOfWork) to the IRepository folder and update the code.
10:35: Add a class UnitOfWork
10:38: Modify the code make public class implements the interface -  UnitOfWork : IUnitOfWork
10:45: register it Startup.cs in the ConfigureServices method 
10:50: add using statements
10:55: build project
11:00: puch commits in github

11:10: Close all currently opened tabs.
11:12: Add a new MVC Controller Empty inside Areas/Admin
11:14: Name it CategoryController.cs
11:16: add using statement IRepository

Do not do after that

11-18-2021
	
18:32: add index file and category controller
18:44: add category drop down
18:52: add icon
19:00: add  category.js file
19:12: create upsert.cshtml file
19:18: create _CreateAndBackToListButton.cshtml file
19:22: create _EditAndBackToListButton.cshtml
19:32: Modify Upsert.cshtml
19:43: add asp-action in index.cshtml

11-22-2021

20:09: code for create category
20:13: add api for delete
20:16: add function delete in category.cs
20:19: add on click event
20:40: edit csproj file
20:42: do not load project in visual studio code 

try for 4 days to solve this problem

11-29-2021 

20:35: Removed Import Group in csproj / Data Access and reloaded the DA project.
20:38: sucessfully load the project

11-30-2021

11:12 add model cover type
11:34 add CoverTypeRepository class 
11:37 add ICoverTypeRepository interface
11:39 add cover type in UnitOfWork
11:40 add cover type in IUnitOfWork
12:29 create  migration database and update databse for covertype
12:36 add cover type in nav bar

12-02-2021

08:40 add product class
08:45 add migration --- 20211202135403_addProductToDb
08:50 update database
08:55 In the SOE review the newly created Products table
09:15 Update the Product class 
09:18 add product repository
09:20 Add IProductRepository Interface
09:25 Add ProductRepository Class and update methid
09:28 add product to unitofwork
09:30 add product to Iunitofwork
09:40 run project and solve error
10:00 Add Product Controller
10:15 Add the IWebHostEvironment call and its using statement to the Microsoft.AspNetCore.Hosting 
10:20 change class to public ProductController method
10:22 Create a ViewModel in the Models project 
10:25 select list for Category and CoverType
10:28 Modify the ProductVM 
10:35 intall the Microsoft.AspNetCore.Mvc.ViewFeatures package.
10:40 Modify the ProductController 
10:41 include the using statements to the ViewModels 
10:45 Comment out the Upsert post method
10:48 Modify the API call to include the Category and CoverType properites
10:51 Add an Index view
10:56 create product.js file
11:00 Modify the _Layout.cshtml to add a new link to Product
11:05 Run the application 
11:10 Create an Upsert.cs for Products
11:15 using the API key provided, initialize and add a function to validate input
11:20 run application
11:24 Add a new folder and subfolder in wwwroot > images/products
11:30 In the ProductController configure the Product Upsert Post action method
11:33 Uncomment the method and modify 

12/6/2021

12:30 Add code on index file for home view
12:40 add code in homecontroller for view
12:45 add data in product file
12:50 run the project
15:52 sucesfully completed project



 



 

































