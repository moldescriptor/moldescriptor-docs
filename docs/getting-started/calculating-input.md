---
sidebar_position: 2
---

# Calculating molecular data from input the field

## Calculating molecular data from input the field
**Single molecule as input**

MolDescriptor takes "simplified molecular-input line-entry system" (SMILES) as input. After the user inputs a SMILES, one can select the descriptors to be calculating by checking the descriptor checkboxes.
Multiple molecules as input

Moldescriptor can take multiple SMILES as input by adding a comma between each molecule. Example of multiple molecules as input:

`n1ccccc1, CN1C=NC2=C1C(=O)N(C(=O)N2C)C, CC(CCOC(=O)CC(C)O)O`


**Error handling**

When you select the "Exclude Invalid SMILES from result" option, any invalid SMILES entries will be excluded from the displayed table on the website. If you do not select this option and an invalid SMILES is inputted, the table will show an "Error" row indicating the invalid SMILES. 