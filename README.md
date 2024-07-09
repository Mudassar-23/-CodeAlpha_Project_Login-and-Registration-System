-> Login and Registration System
This program is a  login and registration system written in C++. 
It allows users to register by creating a username and password, and then log in using those credentials. 
User data is stored in a text file named database.txt.

-> Features
User Registration: Allows new users to register with a username and password.
User Login: Allows registered users to log in with their credentials.
Data Persistence: Stores user credentials in a text file (database.txt) to maintain data between sessions.

-> Program Flow
Menu Display: When the program starts, it displays a menu with three options:
1.Register
2.Login
3.Exit

User Registration:
The user is prompted to enter a username and password.
The username and password are then stored in database.txt.
If the registration is successful, a success message is displayed.

User Login:
The user is prompted to enter a username and password.
The program checks if the credentials match any entry in database.txt.
If the credentials are correct, a success message is displayed. Otherwise, an error message is shown.
Exit: The user can choose to exit the program.
