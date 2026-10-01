Login Database App

A simple Android application demonstrating SQLite database integration and persistent login data storage.

Features
User login interface
SQLite database for storing user information
Database creation and management using SQLiteOpenHelper
Insert and retrieve user data
Persistent local data storage
Simple Android UI
Technologies Used
Android Studio
Kotlin / Java
SQLite
XML
Android SDK
SQLite Classes Used
SQLiteOpenHelper

Used to create and manage the SQLite database.

SQLiteDatabase

Used to perform database operations such as insert, update, delete, and query.

ContentValues

Used to store data as key-value pairs before inserting or updating records.

Cursor

Used to retrieve and read data returned from database queries.

Database

The application creates a local database named:

LoginDatabase.db

The database is stored in the application's private storage:

/data/data/com.example.login_db/databases/

The database can be viewed using Android Studio → App Inspection → Database Inspector.

Project Structure
app
├── manifests
│   └── AndroidManifest.xml
│
├── kotlin+java
│   └── com.example.login_db
│       ├── DatabaseHelper
│       └── MainActivity
│
└── res
    ├── layout
    │   └── activity_main.xml
    └── values
How to Run
Open the project in Android Studio.
Connect an Android device or start an emulator.
Click Run ▶.
The Login application will launch.
Perform the login/database operations.
To inspect stored data, open App Inspection → Database Inspector.
Database Operations

The application demonstrates basic CRUD operations:

Create – Create database and tables
Read – Retrieve stored records
Update – Modify existing records
Delete – Remove records
Author

Akriti Shankar

MCA – Jain (Deemed-to-be University)
