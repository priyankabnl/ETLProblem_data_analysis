# ETLProblem_data_analysis

Write an original ETL code that combines files and identifies cases that have a low blood pressure based on logic below. 

Steps

1)	Identify cases during which blood pressure dropped below the norm for the age (see below) for 14 continuous minutes or longer.

Assume, that the PERSON_ID is the identifier for the patient, and SERVICE_DATE is the date of the surgery that they had. Surgeries don’t span over 1 day. The Age is given for that patient, for the surgery date.  The Blood pressure is only taken during the surgery duration. 

If the child reached 44 months, systolic blood pressure is considered low at 55 mmHg and below. Before 44 months of age, 46 mmHg and below is considered low.

2)	The final report should contain the Person ID, Service date, and duration (in minutes) of the period with low blood pressure.
