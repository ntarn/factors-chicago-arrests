# data

Crimes - 2018.csv

The crimes dataframe is 229,352 observations across 22 variables.

Variables:
1. *`ID`* : Unique numeric identifier for the recorded crime.
  Value - Integer (no particular pattern or order)

2. *`Case Number`* : The Chicago Police Department's RD Number (Records Division
Number), which is unique to the incident.
  Value - Character, string of two letter followed by 5-6 numbers.

3. *`Date`* : Date and time of when the incident occurred. This is sometimes
reported as a best estimate.
  Value - Character, string of date in MM/DD/YYYY format followed by time in
  24-hr format.

4. *`Block`* : Partially redacted address of where the incident occurred, placing
it on the same block as the actual address (actual address is hidden for security
and legal reasons).
  Value - Character
  
5. *`IUCR`* : The Illinois Uniform Crime Reporting code. This is directly linked
to the type and description of the crime reported.
  Value - Character, numeric code.
  
6. *`Primary Type`* : Specific type of crime that was recorded. This is also the
primary description of the IUCR code.
  Value - Character
  
7. *`Description`* : A brief description of what occurred during the recorded
crime. This is also the secondary description of the IUCR code.
  Value - Character
  
8. *`Location Description`* : Description of the location where the incident
occured.
  Value - Character
  
9. *`Arrest`* : Indicates whether an arrest was made.
  Value - Logical (TRUE indicates an arrest was made, FALSE indicates an arrest
  was not made)

10. *`Domestic`* : Indicates whether the incident was domestic-related as defined
by the Illinois Domestic Violence Act. 
  Value - Logical (TRUE indicates domestic-related incident, FALSE indicates non
  domestic-related incident)

11. *`Beat`* : Indicates the beat where the incident occurred. A beat is the
smallest police geographic area - each beat has a dedicated police beat car. 
  Value - Integer 
  
12. *`District`* : Indicates the police district where the incident occurred.
Three to five beats make up a police sector, and three sectors make up a police
district. The Chicago Police Department consists of 22 police districts. 
  Value - Integer
  
13. *`Ward`* : The ward (City Council district) where the incident occurred.
  Value - Integer
  
14. *`Community Area`* : Indicates the commmunity area where the incident
occurred. Chicago has a total of 77 community areas.
  Value - Integer
  
15. *`FBI Code`* : Indicates the crime's classification as outlined in the FBI's
National Incident-Based Reporting System (NIBRS).
  Value - Character
  
16. *`X Coordinate`* : The x-coordinate of the location where the incident
occurred in accordance to the State Plane Illinois East NAD 1983 projection. The
location is shifted from the actual location for partial redaction but falls on
the same block.
  Value - Integer

17. *`Y Coordinate`* : The y-coordinate of the location where the incident
occurred in accordance to the State Plane Illinois East NAD 1983 projection. The
location is shifted from the actual location for partial redaction but falls on
the same block.
  Value - Integer

18. *`Year`* : The year the incident occurred (in this case, since the crimes
dataset is a subset of a larger dataset, every incident occurred in 2018). 
  Value - Integer
  
19. *`Updated On`* : Date and time the record was last updated. 
  Value - Character, string of date in MM/DD/YYYY format followed by time in
  24-hr format.

20. *`Latitude`* : The latitude of where the incident occurred. The location is
shifted slightly from the actual location for partial redaction but falls on the
same block. 
  Value - Double

21. *`Longitude`* : The longitude of where the incident occurred. The location is
shifted slightly from the actual location for partial redaction but falls on the
same block. 
  Value - Double

22. *`Location`* : Coordinates of where the incident occurred. This is a
combination of the variables Latitude and Longitude. 
  Value - Character, coordinate pair.


