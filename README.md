# C Sharp MVC Directory and File Template

#### A quicker start for C Sharp projects

#### By Scott Bergler

## Description
This template will create the directories and basic files needed to start a web project in C Sharp. I adapted it from Sayed I. Hashimi's [article](https://blogs.msdn.microsoft.com/dotnet/2017/04/02/how-to-create-your-own-templates-for-dotnet-new/). The directory structure and file contents are from Epicodus C Sharp curriculum and may not be suited for all projects.

The project files generated will have starter content as outlined in the Epicodus C Sharp course. The template will give relevant namespaces and paths for your project (i.e. MusicOrganizer will be replaced everywhere with the name you give to your project - YourProjectName).

The directory/file structure created is as follows:

```
YourProjectName.Solution
├── README.md
├── .gitignore
└── YourProjectName
    ├── YourProjectName.csproj
    ├── Program.cs
    ├── Startup.cs
    ├── Controllers
    │   └── HomeController.cs
    ├── Models
    ├── wwwroot
    │   └── css
    │   │    └── bootstrap.min.css
    │   │    └── styles.css
    │   └── img
    │   └── js
    │       └── bootstrap.min.js
    │       └── scripts.js
    └── Views
        └── Home
            └── Index.cshtml

└── YourProjectName.Tests
    └── YourProjectName.Tests.csproj
    ├── ModelTests
    │    └── ClassTests.cs
    └── ControllerTests
        ├── ClassControllerTests.cs
        └── HomeControllerTests.cs

```

There is a lot more a person could do with this, but I'm keeping this simple for now, trying to stay within the scope of the type of projects we're currently doing at Epicodus. I will be adding to it as the course continues.

### Specifications:
##### Spec 1: Do a thing:
- [ ] **Expect:** Input: some input; Output: some output;

## Setup/Installation Requirements
Clone the code from [GitHub](https://github.com/skillitzimberg/MusicOrganizer.Solution).

While following this set up guide, replace both the brackets - [] - and the content between them with the information relevant to your situation. This is just an example guide.

Install the template using the command line interface (cli)/terminal:
* dotnet new --install [ /Users/Your/Path/Here ]/MusicOrganizer.Solution

For example: When cloned to the Epicodus computer Desktop, the path would be /Users/Guest/Desktop/MusicOrganizer.Solution.
The above command would then be:
* dotnet new --install /Users/Guest/Desktop/MusicOrganizer.Solution

Navigate to the directory that you want your project to be in (i.e. Desktop, Documents, or wherever you keep your projects).

Run the this command in the cli/terminal:
* dotnet new musicorganizer -n [ YourProjectName ] -o [ YourProjectName ].Solution

For example: If your project is called Banana the command would be:
* dotnet new musicorganizer -n Banana -o Banana.Solution

Open the directory in your text editor. Open the .template.config/template.json file and change the author name to your own. Read the article mentioned above for details on this file and how to this template was created.

## Known Bugs

## Support and contact details
Scott Bergler :: commandinghands@gmail.com

## Technologies Used

HTML, CSS, Json, C#.

### License

Licensed under the MIT license.

Copyright (c) 2018 ** Scott Bergler **
