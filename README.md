# Dr. Sillystringz's Factory

#### By **Amber Wilwand**

#### An application to help Dr. Sillystringz organize his engineers and machines!

## Technologies Used

- C#
- NET 5.0
- dotnet
- Entity Framework
- Bootstrap
- Many to Many relationships

## Description

This application will help Dr. Sillystringz keep track of which engineers are assigned to which machines! Each machine can have multiple workers, and workers can work on the same machine as others! The good doctor can add, edit, and delete both engineers and machines as he sees fit.

## Setup/Installation Requirements

- Clone repository.
- Open code in your favorite text editor. I use VS Code.
- Using MySQL Workbench, import amber_wilwand.sql to create a local instance of the database.
- Create an appsettings.json file in the/HairSalon directory, and input the code { "ConnectionStrings": { "DefaultConnection": "Server=localhost;Port=3306;database=amber_wilwand;uid=root;pwd=[YOUR-PASSWORD];" } }
- Make sure to replace 'YOUR-PASSWORD' with your MySQL Workbench password!
- Head back into the program you're running the code with, and run the command dotnet build in the terminal.
- Now run the command dotnet run, and enjoy pretending to babysit these machines!

## Known Bugs

## License

_Questions? Concerns? Contact me at 1234@internet.com_

Copyright (c) _10/23/2021_ _Amber Wilwand_
