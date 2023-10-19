# Music Streaming Application

Welcome to the Music Streaming Application project! This application allows artists to share their music and users to discover and enjoy a wide range of music. This README provides instructions on how to set up and run the application, as well as details about the scripts used for database creation and management.

## Architecture

![ERD](https://github.com/RuthwikBg/Music-system/assets/113303754/12204aed-9477-467f-899e-d298c96f9116)


## Instructions to Run

Before running the application, please follow these steps:

1. **Database Setup**: Ensure that you have a database server (e.g., Oracle) set up and running.

2. **Enable Database Output**: In SQLDeveloper, go to `View -> Database Output` to view the data returned by SQL queries.

3. **Execute Scripts**: Run the following scripts in the specified order for database setup and application functionality.

## Scripts and Their Functionalities (in Order of Execution)

1. **SUPER ADMIN Script**: This script creates the Application Admin (APP_ADMIN) and grants them necessary privileges.

2. **Table Creation Script**: The APP_ADMIN script creates all the required tables for the application.

3. **Package Creation Script**: The APP_ADMIN script also creates packages for insert, update, and delete procedures.

4. **Data Insertion Script**: Values are inserted into the tables using the APP_ADMIN script.

5. **View Creation Script**: Views are created by the APP_ADMIN script and displayed.

6. **User Roles and Data Script**: User roles (ARTIST_ROLE and USER_ROLE) are created, along with respective artists and users, using the APP_ADMIN script.

7. **Deletion and Reports Script**: This script is executed to demonstrate deletion procedures and display reports.

8. **Artist Script**: The artist script for Taylor is run, allowing Taylor to perform artist-related actions.

9. **User Script**: The user script for John is run, allowing John to perform user-related actions.

These scripts are essential for setting up the database schema, populating it with initial data, and simulating user interactions within the application. 

Feel free to explore the scripts for further details on the database schema and application functionality.

Thank you for using our Music Streaming Application! If you have any questions or need assistance, please don't hesitate to reach out.
