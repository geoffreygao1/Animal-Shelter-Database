# _Animal Shelter_

#### By _Geoffrey Gao_

#### _An application that helps to track animals in a shelter_

## Technologies Used

* _C#_
* _MySQL_
* _Entity Framework Core_
* _ASP.Net Core MVC_

## Description

_This application contains a website that allows a user to track animals in a shelter. The application contains functionality to add, view, and delete animal and properties. The project demonstrates solid understanding of the new concepts from the Database Basics section including  C#, MySQL, and Entity Core Framework._

## Setup/Installation Requirements

* _Clone this repository_
* _Open your shell (e.g., Terminal or GitBash) and navigate into the AnimalShelter directory_
   - _Within this directory ("AnimalShelter"), create a new filed called `appsettings.json`_
   - _Within `appsettings.json`, put in the following code, replacing `uid` and `pwd` with your own username and password for MySQL_
   ```
   {
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=to_do_list_with_ef_core;uid=root;pwd=epicodus;"
  }
  }
  ```
   - _In the terminal, run the program with `dotnet watch run` to start the project in development mode with a watcher_
   - _If the application does not automatically launch, open the browser to [https://localhost:5001](https://localhost:5001)_

## Known Bugs

* _N/A_

## License

_MIT_

Copyright (c) _2023_ _Geoffrey Gao_