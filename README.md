# Public-Dataset-Healthcare-Analytics-EDA
Conducted extensive Exploratory Data Analysis (EDA) based on a publicly available synthetic dataset of ~1000 patients in a Boston based healthcare facility on attributes like Data Sanity Checks, Patient Journeys, Patient Demographics, Payer Analytics etc.
__________________________________
1. The folder "flat-files" contains the Dashboard as well as the relevant flat files generated from Python (with a little manual cleaning in Excel)
2. The folder "raw-files" contains the Python file as well as the raw files in its orginal form. Some additional mappings files have also been made to facilitate the calculations in Pandas
__________________________________
Make sure that the Python file lies in the same directory as the raw files, same applying to the PowerBI Dashboard and the Flat Files.
__________________________________
THe ipynb file contains the following steps in the EDA.
1. Explore the 5 raw tables, describe the shape, head, try getting basic counts and an idea of some parameters and attributes.
2. Explore the Fill Rates of all the tables
3. Start joining tables according to the database schema appropriately with the Primary and Foreign Keys
4. Make flat files for PowerBI which has various counts for Patient level atrributes like demographics, Payers, Procedures, Monthly Counts etc.
