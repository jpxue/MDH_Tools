# MDH Census Creation

Simple tool coded in Javascript which allows you to create a Census from a CPAS comma separated value (.csv) file 
Will calculate the patient's age and sort out the patients by shortest ward round route possible (based of ward locations in Q2 2021).

###### *Mock data (Identification Numbers, Gender, DOB, Locality, LOS & Location) used in the following images for data protection purposes.*

## Instructions

1. Download the .csv file from CPAS
2. Select your Starting Ward (patient list will be devised according from this starting point)
3. Click choose file and open the .csv file downloaded in Step #1
4. Hit CTRL-P to Print

![Instructions](https://github.com/jpxue/MDH_Tools/blob/main/MDH_CPAS_Census/how-to-use.gif)



## Example of a Census
![alt text](https://github.com/jpxue/MDH_Tools/blob/main/MDH_CPAS_Census/output-example.PNG)

Demo: https://jpxue.github.io/MDH_Tools/MDH_CPAS_Census/index.html





# MCH Supervision Forms

Simple JS script embedded in an HTML document to fill in MCH Supervision Forms (can be used offline).

## Instructions
1. Store your sectioned in-patient data in a Spreadsheet (Google Sheets, Excel etc...) as 'Name','Surname','ID','Level','Reason' (refer to [Supervision Forms.xls](https://github.com/jpxue/MDH_Tools/blob/main/MCH_Supervision_Forms/Supervision%20Forms.xlsx)).
2. Copy and paste the in-patient data (fields must be delimited by a 'Tab' - default) in the TextBox
3. Fill in the Ward field or leave it empty (Optional: Designation and Signature fields)
4. Hit Submit
5. CTRL-P to Print the Forms


![Alt Text](https://github.com/jpxue/MDH_Tools/blob/main/MCH_Supervision_Forms/how-to-use.gif)

Demo: https://jpxue.github.io/MDH_Tools/MCH_Supervision_Forms/index.html
