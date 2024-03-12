---
sidebar_position: 3
---

# Working with CSV files

## Calculating molecular data from uploading a CSV file

**Format of uploaded CSV**

The CSV to be uploaded should contain one column of SMILES. 

**Example of a CSV in table format:**

|           |
|-----------|
| C         |
| O=C=O     |
| CCO       |
| C1CCCCC1  |

Calculating molecular data from a CSV file is done by first selecting the descriptors one wants to calculate, then clicking the "Upload CSV" button. This will automatically calculate the contents of the CSV provided it is in the correct format. 

## Downloading the results

After providing the input field with one or many smiles, the user can select the descriptors to be calculated. Pressing the "Download CSV" button will download a CSV file containing the SMILES and the selected descriptors.

When the user inputs the following molecules and select the checkboxes for Number of Atoms, Molecular Weight, Polar Surface Area, and clogP, the system will produce the following CSV:

`Input: CCN(C)C(=O)C, c1ccccc1Cl, C1COCCO1`


| SMILES          | Number of C atoms | Number of Cl atoms | Number of H atoms | Number of N atoms | Number of O atoms | Number of atoms total | MolecularWeight  | PSA                  | clogP                  |
|-----------------|-------------------|--------------------|-------------------|-------------------|-------------------|-----------------------|------------------|----------------------|------------------------|
| CCN(C)C(=O)C    | 5                 | 0                  | 11                | 1                 | 1                 | 18                    | 101.084063972     | 20.31                | 0.4846                 |
| c1ccccc1Cl      | 6                 | 1                  | 5                 | 0                 | 0                 | 12                    | 112.00797784      | 0.0                  | 2.34                   |
| C1COCCO1        | 4                 | 0                  | 8                 | 0                 | 2                 | 14                    | 88.052429496      | 18.46                | 0.0332                 |



The name of the downloaded CSV will contain the name of the current RDKit version: data_RDKit_[current-version].csv

**Error handling**

By selecting the "Exclude Invalid SMILES from result" option, any invalid SMILES will be omitted from the CSV output. If this option is not selected, a new column named "Error" will be added to the CSV to highlight the invalid SMILES entries. 