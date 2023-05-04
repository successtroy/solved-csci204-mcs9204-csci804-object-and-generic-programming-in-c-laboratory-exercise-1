Download Link: https://assignmentchef.com/product/solved-csci204-mcs9204-csci804-object-and-generic-programming-in-c-laboratory-exercise-1
<br>
<strong>Task:</strong> Functions and File I/O <strong>(1.0)</strong>




Define a structure <strong>Pet</strong> consist data fields: status (lost or found), pet type, gender, breeds, age of year, age of month, colour, chip number, location, contact phone number in a file <strong>pet.h</strong>.

Define functions’ prototypes and other necessary definitions in the file <strong>pet.h</strong>.

The data fields’ types are decided by you.

Implement a function countRecords(char *) in a file <strong>pet.cpp</strong> that can return how many records of pets in a given text file. Implement a function loadRecords(char *, Pet *, int) load the pet records in a dynamic Pet array from the given text file. Implement a function printRecords(Pet *, int) print out all the pet records.

The example file <strong>pets.dat</strong> of pet records can be downloaded from the site of the lab task.

Each record stored in one line, different data fields separated by commas except the last field.  There might be some empty lines in a given text file. The empty lines <strong>cannot</strong> be count as the records.

Implement driver program in the main function in <strong>pet.cpp</strong> to get the input text file name from a user, print out number of pet records that stored in the file, load pet records and print out all the data that loaded.




Don’t forget to delete the dynamic pet record array before the program finished.





