**Assignment II: DATABASE CREATION, DELETION AND OEM**

Name: NTAKIRUTIMANA Kevin

ID: 29259

**Task 1: create a new PDB( pluggable database**

CREATE PLUGGABLE DATABASE ke_pdb_29259

    ADMIN USER kevin_plsqlauca_29259 IDENTIFIED BY 12345
    
    FILE_NAME_CONVERT = (
    
        'C:\ORACLE21C\ORADATA\ORCL\PDBSEED\',
        
        'C:\ORACLE21C\ORADATA\ORCL\ke_pdb_29259\'
        
    );
    
<img width="624" height="197" alt="image" src="https://github.com/user-attachments/assets/d18410f8-dd23-4187-aedd-21383a66f51d" />

**Task 2: create and delete a PDB**

      **Creation of a PDB**
      
  CREATE PLUGGABLE DATABASE Ke_to_delete_pdb_29259
  
    ADMIN USER ke_admin IDENTIFIED BY 12345
    
    FILE_NAME_CONVERT = (
    
        'C:\ORACLE21C\ORADATA\ORCL\PDBSEED\',
        
        'C:\ORACLE21C\ORADATA\ORCL\Ke_to_delete_pdb_29259\'
        
    );

<img width="624" height="175" alt="image" src="https://github.com/user-attachments/assets/0c4361ee-73a5-49bf-8e20-aaee8694087f" />

    **Deletion of a PDB**
    
DROP PLUGGABLE DATABASE Ke_to_delete_pdb_29259 INCLUDING DATAFILES;

<img width="624" height="96" alt="image" src="https://github.com/user-attachments/assets/578a0910-f0cf-4c2f-b53a-7a1cb53aa579" />

**Task 3: Oracle Enterprise Manager**

<img width="524" height="232" alt="image" src="https://github.com/user-attachments/assets/85d31b8d-4612-42b1-ab1c-73011fd16eee" />







    
  
