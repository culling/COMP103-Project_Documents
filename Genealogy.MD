
## Genealogy 
![Screenshot from image](docs/Genealogy-screenshot-01.png)
### Purpose - Display Genealogy information
### Intro
Genealogy is a program for a simple genealogical database. The database contains information about many people, including their name, year of birth, the names of their parents (if known), and the names of their children (if known). Unlike real genealogical databases, this one has very "clean" data. In particular, every person has a unique name! It is also simple so that it doesn't record marriages or dates other than year of birth.

The data is stored in a file named database.txt that contains one line for each person in the database. The file has names of the person's parents, when known, but doesn't have any names of their children. The information in the file should be loaded into a Map where the key is the name of a person, and the value is a Person object that contains the information about that person.

### Details
Given a simple and incomplete implementation of the Genealogy program I added or completed the additional functions.

+ Load data from file 
+ Print all details - full details of ever person in the database
+ Select or add a person them if they don't exist
+ Print children, grandchildren and parents
+ Automatically fix the database (Updating children of parent based on children's parents - some of the file details were incorrect)
+ Find and print any missing parents or children which do not exist in the database (eg. children referenced in the parents entry, not listed in the database)
+ Print out ancestry trees and descendant trees

I was also able to implement consistency checks including
+ No one should be born before either of their parents.
+ The parents' ages should not be too far apart
+ No one should be their own ancestor.
