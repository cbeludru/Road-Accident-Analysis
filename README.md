# UK Road Accidents Analysis

**Purpose:**

Demonstrate analysis of large dataset using python.

<br>

**Data used for analysis:**

All STATS19 data (accident, casualties and vehicle tables) for 2005 to 2014 (zipfile size: 108 MB)
http://data.dft.gov.uk.s3.amazonaws.com/road-accidents-safety-data/Stats19_Data_2005-2014.zip

The zipfile includes 3 files:
1. Accidents0514.csv (225.3 MB)
2. Casualties0514.csv (99.6 MB)
3. Vehicles0514.csv (189.7 MB)

These files provide detailed road safety data about the circumstances of personal injury road accidents in GB from 2005 to 2014. the types (including Make and Model) of vehicles involved and the consequential casualties. All the data variables are coded rather than containing textual strings. 

List of variables in the dataset:

| Accident Circumstances                                             | Vehicle                          | Casualty                                       |
|--------------------------------------------------------------------|----------------------------------|------------------------------------------------|
| Accident Index                                                     | Accident Index                   | Accident Index                                 |
| Police Force                                                       | Vehicle Reference                | Vehicle Reference                              |
| Accident Severity                                                  | Vehicle Type                     | Casualty Reference                             |
| Number of Vehicles                                                 | Towing and Articulation          | Casualty Class                                 |
| Number of Casualties                                               | Vehicle Manoeuvre                | Sex of Casualty                                |
| Date (DD/MM/YYYY)                                                  | Vehicle Location-Restricted Lane | Age of Casualty                                |
| Day of Week                                                        | Junction Location                | Age Band of Casualty                           |
| Time (HH:MM)                                                       | Skidding and Overturning         | Casualty Severity                              |
| Location Easting OSGR (Null if not known)                          | Hit Object in Carriageway        | Pedestrian Location                            |
| Location Northing OSGR (Null if not known)                         | Vehicle Leaving Carriageway      | Pedestrian Movement                            |
| Longitude (Null if not known)                                      | Hit Object off Carriageway       | Car Passenger                                  |
| Latitude (Null if not known)                                       | 1st Point of Impact              | Bus or Coach Passenger                         |
| Local Authority (District)                                         | Was Vehicle Left Hand Drive      | Pedestrian Road Maintenance Worker (From 2011) |
| Local Authority (Highway Authority - ONS code)                     | Journey Purpose of Driver        | Casualty Type                                  |
| 1st Road Class                                                     | Sex of Driver                    | Casualty IMD Decile                            |
| 1st Road Number                                                    | Age of Driver                    | Casualty Home Area Type                        |
| Road Type                                                          | Age Band of Driver               |                                                |
| Speed limit                                                        | Engine Capacity                  |                                                |
| Junction Detail                                                    | Vehicle Propulsion Code          |                                                |
| Junction Control                                                   | Age of Vehicle (manufacture)     |                                                |
| 2nd Road Class                                                     | Driver IMD Decile                |                                                |
| 2nd Road Number                                                    | Driver Home Area Type            |                                                |
| Pedestrian Crossing-Human Control                                  |                                  |                                                |
| Pedestrian Crossing-Physical Facilities                            |                                  |                                                |
| Light Conditions                                                   |                                  |                                                |
| Weather Conditions                                                 |                                  |                                                |
| Road Surface Conditions                                            |                                  |                                                |
| Special Conditions at Site                                         |                                  |                                                |
| Carriageway Hazards                                                |                                  |                                                |
| Urban or Rural Area                                                |                                  |                                                |
| Did Police Officer Attend Scene of Accident                        |                                  |                                                |
| Lower Super Ouput Area of Accident_Location (England & Wales only) |                                  |                                                |




<br>

**Guide for the data:**

Road Accident Safety Data Guide <br>
http://data.dft.gov.uk/road-accidents-safety-data/Road-Accident-Safety-Data-Guide.xls


