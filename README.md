# CSC471: Database Management Systems Final Project

This project focused on implementing a user interface that appropriately writes, reads, updates, deletes, and displays members and entries of a database system. This project focused on representing relationships between different game objects and to store/organize the appropriate information about each object using relational databases. 

This is the ER diagram for the project: [DBMS ER Diagram](https://github.com/racheljohnston0/DBMSFinalProject/assets/144559202/8505398c-374e-4b8b-b082-76e5650f2303)

This is a visualization of relational database for the project: [DBMS Relations](https://github.com/racheljohnston0/DBMSFinalProject/assets/144559202/adb8108d-4856-49a4-92b4-8a2bfd187885)

```DisplayOne.java```: UI that deals with the character table and all of it's related attributes/tables.

```DisplayTwo.java```: UI that handles players of the game and all of it's related attributes/tables.

```DisplayThree.java```: UI that takes care of all weaponns in the game and all of it's related attributes/tables.

```DisplayFour.java```: UI that manages the different locations of the game and all of it's related attributes/tables.

```ConnectivityFramework.java```: creates a singleton JDBC connection to the database so it can be used by each of the displays.
