# dotnet-Core-MVC-Intro
Introduction to dotnet core MVC

MVC stands for Model View Controller and is a software architectural pattern that separates and app into three interconnected parts:

- Model:
  - It represents data amd business logic of the app.
  - It is responsible for managing the data and enforcing the application's business rules like data validation.
- View: 
  - It represents the user interface of the app.
  - It is responsible for displaying the data to the user and receiving user input
- Controller:
  - It acts as an intermediary between the model and view.
  - It is responsible for processing user input, updating the model and selecting an appropriate view to display the updated data.
  - It ensures data coordination between view and model
    - It takes data from model and pass it to the view and vice-versa.
  
## Benefits of MVC Implementation to Software Development:
- Improved Separation of Concerns
- Greater Flexibility
- Better Maintainabily.

## How to create dotnet project using CLI?
- dotnet --version
  - To check dotnet version if it is installed.
  - If it is not installed, you need to to do so.
- cd Desktop
  - Go to the directory where you want to create your mvc project. In our case, it is desktop.
- mkdir App
  - Make a folder App
- cd App
  - Get inside the folder.
- dotnet new mvc --name firstCoreAPP
  - Create an asp.net core mvc project named firstCoreAPP
- cd firstCoreAPP
  - Get inside the created folder.
- dotnet build
  - Build the app.
- dotnet run
  - Run the application, you will see a url, copy and paste that url in your browser in order to see the outcome.
- Hurray! We're done with our dotnet project using CLI.
