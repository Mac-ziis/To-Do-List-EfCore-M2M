## How To Run This Project


    Clone this repo.
    Open the terminal and navigate to this project's production directory called "ToDoList".
    Within the production directory "ToDoList", create a new file called appsettings.json.
    Within appsettings.json, put in the following code, replacing the uid and pwd values with your own username and password for MySQL. For the LearnHowToProgram.com lessons, we always assume the uid is root and the pwd is epicodus.

{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=to_do_list_with_ef_core;uid=root;pwd=epicodus;"
  }
}

Within the production directory "ToDoList", run dotnet watch run in the command line to start the project in development mode with a watcher.
Open the browser to https://localhost:5001. If you cannot access localhost:5001 it is likely because you have not configured a .NET developer security certificate for HTTPS.