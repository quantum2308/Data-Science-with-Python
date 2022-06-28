# Data-Science-with-Python
This project Perform a service request data analysis of New York City 311 calls. Focused on the data wrangling techniques to understand the pattern in the data and also visualize the major complaint types.

Performed a service request data analysis of New York City 311 calls. 

Converted the columns ‘Created Date’ and Closed Date’ to datetime datatype and created a new column ‘Request_Closing_Time’ as the time elapsed between request creation and request closing.

Provided major insights/patterns that we can offer in a visual format (graphs or tables).  

4 major conclusions after generic data mining.

Ordered the complaint types based on the average ‘Request_Closing_Time’, grouped them for different locations.

Performed a statistical test for the following:
Whether the average response time across complaint types is similar or not (overall)
Are the type of complaint or service requested and location related?

Dataset Description :

Field	Description
Unique Key	(Plain text) - Unique identifier for the complaints
Created Date	(Date and Time) - The date and time on which the complaint is raised
Closed Date	(Date and Time)  - The date and time on which the complaint is closed
Agency	(Plain text) - Agency code
Agency Name	(Plain text) - Name of the agency
Complaint Type	(Plain text) - Type of the complaint
Descriptor	(Plain text) - Complaint type label (Heating - Heat, Traffic Signal Condition - Controller)
Location Type	(Plain text) - Type of the location (Residential, Restaurant, Bakery, etc)
Incident Zip	(Plain text) - Zip code for the location
Incident Address	(Plain text) - Address of the location
Street Name	(Plain text) - Name of the street
Cross Street 1	(Plain text) - Detail of cross street
Cross Street 2	(Plain text) - Detail of another cross street
Intersection Street 1	(Plain text) - Detail of intersection street if any
Intersection Street 2	(Plain text) - Detail of another intersection street if any
Address Type	(Plain text) - Categorical (Address or Intersection)
City	(Plain text) - City for the location
Landmark	(Plain text) - Empty field
Facility Type	(Plain text) - N/A
Status	(Plain text) - Categorical (Closed or Pending)
Due Date	(Date and Time) - Date and time for the pending complaints
Resolution Action Updated Date	(Date and Time) - Date and time when the resolution was provided
Community Board	(Plain text) - Categorical field (specifies the community board with its code)
Borough	(Plain text) - Categorical field (specifies the community board)
X Coordinate	(State Plane) (Number)
Y Coordinate	(State Plane) (Number)
Park Facility Name	(Plain text) - Unspecified
Park Borough	(Plain text) - Categorical (Unspecified, Queens, Brooklyn etc)
School Name	(Plain text) - Unspecified
School Number	(Plain text)  - Unspecified
School Region	(Plain text)  - Unspecified
School Code	(Plain text)  - Unspecified
School Phone Number	(Plain text)  - Unspecified
School Address	(Plain text)  - Unspecified
School City	(Plain text)  - Unspecified
School State	(Plain text)  - Unspecified
School Zip	(Plain text)  - Unspecified
School Not Found	(Plain text)  - Empty Field
School or Citywide Complaint	(Plain text)  - Empty Field
Vehicle Type	(Plain text)  - Empty Field
Taxi Company Borough	(Plain text)  - Empty Field
Taxi Pick Up Location	(Plain text)  - Empty Field
Bridge Highway Name	(Plain text)  - Empty Field
Bridge Highway Direction	(Plain text)  - Empty Field
Road Ramp	(Plain text)  - Empty Field
Bridge Highway Segment	(Plain text)  - Empty Field
Garage Lot Name	(Plain text)  - Empty Field
 
Ferry Direction	(Plain text)  - Empty Field
Ferry Terminal Name	(Plain text)  - Empty Field
Latitude	(Number) - Latitude of the location
Longitude	(Number) - Longitude of the location
Location	(Location) - Coordinates (Latitude, Longitude)


# Requirements to run Project:
1. You should have python install (prferabaly python 3).
2. Extract the data set and put it in the same folder as the executable ipynb file.

NOTE:- Data set and Project statements are taken from Simplilearn.
