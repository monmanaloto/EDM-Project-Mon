# Transforming ER Model to Relational Tables

## *Create the Student Table with Fields*

- username (STRING, VARCHAR(50), PRIMARY KEY)

<img src="Images/Stu_sub.png" alt="Alt Text" width="400" height="300">

## *Create the Assignment Table with fields*

- shortname (STRING, VARCHAR(50), PRIMARY KEY)
- due_date (DATE, NOT NULL)
- url (STRING, VARCHAR(255), NOT NULL)

  <img src="Images/Assign_table.png" alt="Alt Text" width="400" height="300">

  ## Create the Submission Table with fields

  username (VARCHAR(50))

- shortname (VARCHAR(50))
- version (INT)
- Submit_date (DATE, NOT NULL)
- data (TEXT)

  <img src="Images/Stu_sub.png" alt="Alt Text" width="400" height="300">

  ## EER Diagram

  <img src="Images/Stu_sub.png" alt="Alt Text" width="400" height="300">
