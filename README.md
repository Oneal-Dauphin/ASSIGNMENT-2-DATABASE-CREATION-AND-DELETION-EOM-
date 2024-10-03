# ASSIGNMENT-2-DATABASE-CREATION-AND-DELETION-EOM-



CREATING DATABASE
************************

CREATE PLUGGABLE DATABASE plsql_class2024db
ADMIN USER on_plsqlauca IDENTIFIED BY Dauphin
FILE_NAME_CONVERT = ('C:\app\envy\product\21c\oradata\xe\pdbseed\', 'D:\oracle21c\oradata\ORCL2\orclpdb\plsql_class2024db\');



CREATE PLUGGABLE DATABASE on_to_delete_pdb
ADMIN USER on_plsqlauca IDENTIFIED BY Dauphin
FILE_NAME_CONVERT = ('C:\app\envy\product\21c\oradata\xe\pdbseed\', 'D:\oracle21c\oradata\ORCL2\orclpdb\on_to_delete_pdb\');




DELETING DATABASE
************************

DROP PLUGGABLE DATABASE ON_TO_DELETE_PDB INCLUDING DATAFILES;




# Oracle Pluggable Database Creation

## Overview
This repository documents the process of creating and managing pluggable databases (PDBs) in an Oracle database environment. It includes steps to create a PDB for class activities and a temporary PDB for testing purposes.
