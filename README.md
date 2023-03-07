# Animal Shelter

#### By: **Brishna Bakshev and Owen Brown**

## Technologies Used

* C#
* Razor HTML
* .Net 6
* MySQL
* Entity Frameworkd Core 6

## Description

_This application will prompt the user to create a tracker for the animals up for adoption. The User can add a new animal to the database or the user can view all animals currently up for adoption._

## Setup/Installation Requirements

#### You will need:
* A code editor, such as [VS Code](https://code.visualstudio.com/)
* [Git](https://github.com/) installed
* [Install .Net 6 SDK:](https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-c-and-net)

#### [Install MySQL Workbench:](https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql)
* After following the MySqlWorkbench installation instructions, open MySql Workbench and select the Local 3306 server. Then select the "Administration" tab and click on "Data Import/Restore"
* In Import Options select "Import from Self-Contained File" and click the "..." button to navigate to the file "Dump20230306.sql" in the top level of this repository.
* Under the "Default Schema to be Imported to" select "New..." and enter schema name Dump20230306. Click "Start Import" in the bottom right
* Confirm the import was successful by clicking on the "Schemas" tab and seeing the Dump20230306 schema listed.
*  Navigate to the local directory (YourPath/AnimalShelter.Solution/AnimalShelter) and create a new file "appsettings.json"
* Open the file in VS Code and add:

```sh
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=[YOUR-DB-NAME]µ;uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
  }
}
```
**IMPORTANT**: Replace [YOUR-USERNAME-HERE] and [YOUR-PASSWORD-HERE] with the your own user and password values, and [YOUR-DB-NAME] with any name you'd like to call the database, i.e. "animal_shelter"


#### Open Terminal (not including the dollar symbol):
```sh
  $ cd Desktop
  $ git clone https://github.com/bbakshev/AnimalShelter.Solution.git
  $ cd AnimalShelter.Solution
```



#### To run the program in the terminal use the following command (not including the dollar symbol):

```sh
$ dotnet watch run ./AnimalShelter
```

## Known Bugs

* None

## License

[MIT](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)

Copyright (c) 2023 Brishna Bakshev and Owen Brown