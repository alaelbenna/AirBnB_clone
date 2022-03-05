# AirBnB clone - The console
## About
* This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration… This project was created to Holberton School.
## Usage
* Like the Unix shell, the HBnB console works in both interactive and non-interactive modes. In interactive mode, it prints a prompt and waits for input from the user.
## First step:
Write a command interpreter to manage your AirBnB objects. This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration… we put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel create the first abstracted storage engine of the project: File storage. create all unittests to validate all our classes and storage engine.
## COMMAND | DESCRIPTION
To begin interactive mode, run ./console.py from the command line
| COMMAND                                                       | DESCRIPTION |
| (hbnb) quit                                                   | Quits console |
| (hbnb) EOF                                                    | Quits console via EOF |
| (hbnb) help <command>                                         | Display help for |
| (hbnb) create <class>                                         | Create object and print id |
| (hbnb) show <class> <id>                                      | Show information about an object |
| (hbnb) destroy <class> <id>                                   | Destroy object |
| (hbnb) all <class>                                            | Show all instances of a class |
| (hbnb) update <class> <id> <attribute name> <attribute value>	| Creates or updates the attribute of a class |
## Files Used in this Project
## Built With
## Authors
