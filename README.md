## Project: Real Estate Management System

**Description:**

The Real Estate Management System is a web application built on ASP.NET Core MVC (.NET 8) with Entity Framework Core, providing a comprehensive solution for managing assets, owners, and tenants in a real estate scenario. The project incorporates CRUD operations with a Master-Details pattern and includes image upload functionality. AJAX with jQuery is utilized for a seamless user experience, and the entire CRUD functionality is implemented through stored procedures.

This is a POC project for Santos Real Estate Holdings Inc. in NB, Canada.  

**Technologies:**

* **Backend:** ASP.NET Core MVC (.NET 8), Entity Framework Core, SQL Server (with Stored Procedures)
* **Frontend:**  AJAX with JQuery
* **Additional features:** ViewComponents, Partial Views

**Key Functionalities:**

* Manage three fundamental entities: Assets, Owners, and Tenants.
* Perform CRUD operations for each entity through controllers (AssetsController, TenantController) and HomeController.
* Utilize Stored Procedures for efficient database interaction.
* Leverage AJAX with JQuery for dynamic and interactive UI updates.
* Employ ViewComponents and Partial Views for modular and reusable UI elements.
* Enhance data visualization with image upload capabilities for assets.

**Target Audience:**

This Estate Management System caters to individuals and organizations responsible for managing property portfolios, including:

* Real estate agencies
* Property management companies
* Individual landlords
* Building managers

**Getting Started:**

1. Clone the repository.
2. Install required dependencies (refer to .NET 8 configuration).
3. Configure the connection string for your SQL Server database, in Program.cs 
    See https://learn.microsoft.com/en-us/sql/tools/visual-studio-code/sql-server-develop-use-vscode?view=sql-server-ver16 for details on using the sql server extension https://learn.microsoft.com/en-us/sql/tools/visual-studio-code/sql-server-develop-use-vscode?view=sql-server-ver16 in Visual Studio Code.
4. Build and run the solution using Visual Studio 2022 or latest.
5. Access the application through the browser by navigating to the specified URL.

**Further Development:**

The current version lays a solid foundation for further enhancements, such as:

* Implementing user authentication and authorization for secure access control.
* Integrating payment gateways for rent collection and other financial transactions.
* Introducing reporting and analytics features for data-driven decision making.
* Developing mobile applications for on-the-go property management.


**Disclaimer:**

This project is a POC in progress, provided as a public repo for educational purposes and free for non-commercial use. Other similar repos are found here in github. Please modify and use it according to your specific requirements and adhere to relevant licenses for any external libraries or components. 

**Contact:**

For any questions, feedback, or suggestions, please do not hesitate to contact LSantos2000@gmail.com 



