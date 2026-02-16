# READ.MD
## ABOUT
This assignment is about oracle21c with oracle entreprise manager.
It teaches how about creation and deletion of pluggable databases in a multitenant architecture
### Info
* **Name:** Fiacre Ishimwe
* **Student ID:** 29126
* **Date:** February 13, 2026

# TASK OVERVIEW
## TASK 1
* ### Creating pluggable database named fi_pdb_29126
This pdb was created in the installation process of oracle21c
* ### Creating a user inside pluggable database named fi_plsqlauca_29126
#### Sql command for creating
create user fi_plsqlauca_29126
identified by 1234;
## TASK 2
* ### Creating temporary pluggable database named fi_to_delete_pdb_29126
#### Sql command for creating temporary pdb
create pluggable database fi_to_delete_pdb_29126 
admin user fi_to_delete_pdb_29126 identified by 1234
file_name_convert = ('C:\oracle21c\orcl\pdbseed', 'C:\oracle21c\orcl\fi_to_delete_pdb_29126')
#### SQL command for viewing pdb
show pdbs;
#### SQL command for deleting pdb
drop fi_to_delete_pdb_29126 including datafiles;
#### Sql command to show pdb no longer exists
show pdbs;
## TASK 3
This task was about showing that we had configured our enterprise manager and we had to take a screenshot which i provided in my folder assignment2.

 ## Challenges.
 Like every assignment it's supposed to challenge us and personally the issues i faced i managed to find solutions from these creators and i give credibility to their work.
 * **CREATING MULTITENANT DATABASE** : https://www.youtube.com/watch?v=dPHerZHvUyk
 * **HOW TO CREATE A PLUGGABLE DATABASE** : https://www.youtube.com/watch?v=HbLeZjwbZg0
 * **SOME SQL COMMANDS** : https://www.w3schools.com/sql/sql_syntax.asp


