Description : 

Biological Sequence Manager is a Python application with a user interface built using PyQt5. It enables the management of a MySQL database (via XAMPP) for analyzing DNA sequences. The application    calculates several biological properties, including:

    GC Percentage: Measures the proportion of guanine (G) and cytosine (C) bases in a sequence.
    Nucleotide Chemical Property (NCP): Computes metrics based on the chemical properties of nucleotides.
    Nucleotide Density (ND): Analyzes the correlation between nucleotide position and frequency.
    Electron-Ion Interaction Pseudopotential (EIIP): Represents the energy of delocalized electrons in the sequence.

The interface also allows users to add, delete, and import sequences from a CSV file and download the entire database.

Features :

    Add DNA Sequence: Add a new DNA sequence to the database.
    Delete Sequence: Remove a selected sequence from the database.
    Import CSV File: Load sequences and associated data from a CSV file.
    Export Database: Download the complete database as a file.
    Automatic Calculations:
        GC Percentage.
        NCP, ND, and EIIP values.
        
Requirements :

    Python 3.7 or higher
    Python Libraries:
        PyQt5
        mysql-connector-python
        pandas
    Local Server: XAMPP
    MySQL database 
    
Usage :

    Add a Sequence: Enter a sequence in the input field and click the Add button.
    Delete a Sequence: Select a row from the table and click Delete.
    Import CSV File: Click Import CSV to upload bulk data.
    Export the Database: Click Download Database to export all sequences.    
        
        
