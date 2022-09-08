1. Project's Title
Blazing Pizza

2. Project Description
A single page application built with the Blazor framework, this is a simple Pizza store application that allows you to place an order,
add additional items to an order and view the status of an order. I used Blazor because the the SPA layout for overlaying pages 
is robust and translates well for navigation. All "pages" are anchored onto the MainLayout.razor component. The framework also allows
individual components to be defined and called using delegates and events so an individual page doesnt need to have multiple callback methods.
Components are reusable in different pages so that adds to the robustness of the code (less coupling) and with Blazor WebAssembly the C# 
code is run in browser with almost the same speed as native browser code. The project structure also organizes server side and client side
code conviniently allowing for the same code and framework to be used consistently across the application stack. 

The back-end is built with EntityCoreFramework, this framework is convinient because it uses a code first approach so the Database is built first
and allows db configuration as opposed to working on an existing db. Querying the DB is done via entities. DB mappings can bre designed visually.The boiler plate code for a lot of the mappings is auto-generated so development is much faster and less tedious.

3. How to run the Application
- Clone the given repo (https://github.com/Choki12/BlazingPizza.git)
- Run the BlazingPizza.sln file
- Ensure the start-up project is BlazingPizza.Server
- Run the application 
