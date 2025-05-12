
# This repository contains my MongoDB CRUD operations checkpoint completed using MongoDB Compass.



# This is a Word document with screenshots.

# Step taken in creating the screenshots;

-Log into my MongoDB Compass (GUI) account
-create a database named 'contact' and a collection named 'contactlist'
-insert the data using Compass 'Insert Document' tab.
-caryy out the following CRUD operations and took the screenshots of each.

-Display all the information about only one person using his ID( { "_id": ObjectId("...") }).
-Display all the contacts with an age >18 ({ "age": { "$gt": 18 } }).
-Display all the contacts with an age>18 and name containing "ah"({
  "age": { "$gt": 18 },
  "$or": [
    { "first_name": { "$regex": "ah", "$options": "i" } },
    { "last_name": { "$regex": "ah", "$options": "i" } }
  ]
}).
-Change the contact's first name from"Kefi Seif" to "Kefi Anis"({ "last_name": "Kefi", "first_name": "Seif" } and edit with edit icon).
-Delete the contacts that are aged under <5 ({ "age": { "$lt": 5 } } and used Compass trash icon to delete the date).
-Display all of the contacts list (with the filter empty click 'Find' tab to display all data).

 
# Tools Used

- MongoDB Compass
- Visual Studio Code
- Git & GitHub
- MS Word

# Feel free to explore the `.docx` file to see the final project.
