## Organisation Chart
![Screenshot from image](docs/OrganisationChart-screenshot-01.png)
### Purpose - Allow for an organisation chart to be displayed and edited

### Intro
Many organisations are structured in a hierarchy with a CEO at the top, and then all the other employees below in a management hierarchy.

You are to complete the OrganisationChart program which allows the user to display and edit a chart of an organisation structure that displays the structure as a tree of employees with the CEO at the root of the tree. The links in the tree represent the management structure.

The main data structure in the program is a general tree of Employee objects, where the tree structure is stored directly in the fields of the Employee objects.

### Details 
Given an incomplete implementation of an organisation chart program I implemented the additional functions.
+ Add and remove employees from the tree
+ Retire line managers while keeping their position
+ Save and load employees and thier relationships to a CSV file
+ Automatically draw the Org Chart