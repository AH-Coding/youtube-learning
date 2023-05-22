# Day 1 | Databases [AH-CODING]
<a href="https://www.youtube.com/@AHCoding" target="_blank">Visit Youtube</a>
```
Short Description: This is the first document that you guys are getting
through my first video on MySQL on Youtube, feel free to read all the
things that were tought on youtube and make sure to practice these codes
on your own...
```
### _Creating Database_
Creating a Database is really easy, we only need to write
```
CREATE DATABASE mydb;
```
The following query will create a new Database by the name of mydb and it is essential to put a `;` after we are finished typing our command as the program only understands that a certain command is over when it reads the `;` character.

### _Using a Database_
In order to use a database we need to type
```
USE mydb;
```
It is that simple, it is preferred that we type all the keywords as upper-case words, as this is a better approach in understanding what is value and what is a keyword. We know that the keywords are colored and easy to differentiate but this is a more of a professional and practical approach.

### _Droping a Database_
Droping a database means that we are deleting a database from the schema, and that it will not be accessable any longer after we execute the command.
```
DROP DATABASE mydb;
```
The following command deletes the database, and that database is no longer available to use.

### _Setting Database to be READ-ONLY_
We can alter certain attributes of a database by the `ALTER` keyword but in this example we will be turning the database into a read-only which means that we cannot edit or delete that database. In order to do this, we will type
```
ALTER DATABASE mydb READ ONLY = 1;
```
We are setting the `READ ONLY` attribute's value to 1 which stands for `true` which is know as a boolean value, if the `READ ONLY` attribute is `true` then we will not be able to delete or edit the selected database.

So let's think as if the Database was a folder and all the files within that folder are the tables.