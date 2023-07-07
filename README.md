# TendoProject
Pyspark script along with target file is uploaded.

The insights team has received a new data set from one of our customers for analysis. The data contains information about some of their patient population medical history. The team needs the data to be transformed into a particular format that can be fed into their predictive models.
As a data engineer, you are asked to generate a file as follows:

Output File 
Field Name	Comments
patient_id	Patient ID from the patient table
Sex	As is value from the patient table
Age	As is value from the patient table
primary_care_provider	As is value from the patient table
medication_simple_generic_name	As is value from the medications table
avg_minimum_dose	Calculated average of minimum dose value {minimum_dose} from the medications table 
dose_unit	Unit of the dose from the medications table
admit_diagnosis	As is value from the encounter table

Output File Structure Details:
File name: target_1_YYYYMMDD.txt
Field delimiter: pipe (|) preferred
End of line: Unix style (\n)
Text qualifier: (")
Character encoding: UTF-8
Header: Contains the field names delimited with the same field delimiter define above

Part 1 Deliverables
Show the code you used to generate the file preferably in a git repo.
It's highly recommended that you use a single pyspark or scala script to accomplish this task.
Show the output file as described in the requirements section.
❗If you decide to use spark sql for your solution, explain why you opted for this option instead of using the spark API.

