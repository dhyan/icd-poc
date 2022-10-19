# Get latest [ICD-2023](https://www.cdc.gov/nchs/icd/Comprehensive-Listing-of-ICD-10-CM-Files.htm) data built into json format.
## Provides an easy way to visualize icd codes(check demo), adds script for extracting data from (open source)files provided [here](https://www.cms.gov/medicare/icd-10/2023-icd-10-cm) 

<br />

# Script for building data.
`// Written in python 3 jupyter notebook, retunrs json of icd data, along with nested parent-child levels.` <br />

    src/notebook/final_icd_json.ipynb

# Need the final json ouput only? Copy json file from below path.
    src/app/test-data.json

# Local development(uses node 16 and angular 14)?
    // Clone this repo.
    npm install
    ng serve

# [Demo ⚡️](https://stackblitz.com/edit/angular-ryuedn)