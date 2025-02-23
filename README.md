# LostNfound
# User Guide for Lost and Found System
This guide explains how to use the Lost and Found Management System step by step.

# Introduction
This system allows users to report lost and found items, search for lost items, and manage the item list. It supports two types of users:
Students – Can report lost items and search for items.
Admins – Can add, remove, edit, and search for lost items.

# How to Run the Program
Step 1: Compile and Run the Program
Open a terminal or command prompt.
Navigate to the directory where the C++ file is saved.
Compile the program using:
bash
CopyEdit
g++ lost_found.cpp -o lost_found


Run the program using:
bash
CopyEdit
./lost_found



Step 2: Login Process
When you run the program, you will see the following menu:
pgsql
CopyEdit
How would you like to login
1. Student
2. Admin
0. To exit the program

Choosing the Login Type
Enter 1 if you are a Student.
Enter 2 if you are an Admin.
Enter 0 to exit the program.

Student User Flow
If you select 1. Student, you will see this menu:
pgsql
CopyEdit
<== Lost and Found ==>
1. Add a lost item
2. Lost items List
3. Search an item
0. To change user

1. Add a Lost Item
Select 1 to add an item to the lost and found system.
Enter the following details:
mathematica
CopyEdit
Enter item code: 101
Enter item name: Laptop
Enter item color: Black
Enter item brand: Dell
Identification mark (if any): Small scratch on the lid
Enter the place where the item was found: Library
Enter your name: Shrey Rastogi
Enter your student ID: SRM123
Enter your contact number: 9876543210


The item will be saved in the items.txt file, and you'll see:
mathematica
CopyEdit
Item added successfully


2. View Lost Items List
Select 2 to see all lost items in a table format.
3. Search for a Lost Item
Select 3 to search for an item by name.
Enter the item name, and if found, details will be displayed.
yaml
CopyEdit
Enter name of the item: Laptop


4. Exit or Change User
Select 0 to go back to the login menu.

Admin User Flow
If you select 2. Admin, you will be prompted to enter a password:
nginx
CopyEdit
Please enter the password

Enter 1234 (default password).
If you enter the wrong password, you’ll be asked to enter it again.
Once logged in as Admin, you will see:
markdown
CopyEdit
<== Lost and Found ==>
1. Add a lost item
2. Lost items List
3. Remove a lost item
4. Edit information about a lost item
5. Search an item
0. Change user

1. Add a Lost Item
Same as the Student section.
2. View Lost Items List
Same as the Student section.
3. Remove a Lost Item
Select 3 to delete an item.
Enter the item code to remove it.
css
CopyEdit
Enter the item code to remove: 101


If the item is found, it will be removed.
nginx
CopyEdit
Deleted successfully


If not found:
pgsql
CopyEdit
Record not found!


4. Edit an Item
Select 4 to edit an item's details.
Enter the item code.
You will be asked if you want to update each field (y/n for yes/no).
pgsql
CopyEdit
Do you want to change the item name? (y/n)
Enter new item name: MacBook


5. Search for an Item
Same as the Student section.
6. Exit or Change User
Select 0 to return to the login menu.

End of User Flow
At any point, the program will ask:
vbnet
CopyEdit
Do you want to continue? (y/n)

Enter y to continue.
Enter n to exit the program.

Conclusion
This system helps in managing lost and found items efficiently. Admins have full control over items, while students can report and search for their lost belongings. 🚀

