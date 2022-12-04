# Hospital-Directory-Using-py3
Program using Python3 that makes use of webpage parsing to read through different webpages, specifically the official websites of particular hospitals in and around Coimbatore , to extract information about the doctors and specialties available at a particular hospital.
This project has collected the required information from 2 hospitals namely,
		-KMCH  (https://kmchhospitals.com/kmch-main-center/)
	-Sheela Hosptial (http://www.sheelahospital.in/department/)
The extracted information is stored in the form of dictionaries in a JSON file. The same file is used to search and display the information required by the user.
The user is initially given 2 choices:
	-To search by Hosptitals
	-To search by Specialities
If the user decides to search by hospitals, they are allowed to pick a hospital and are then presented with the different doctors available at the hospital.
Alternatively, if the user decides to search by speciality, a list of specialities is displayed for the user to pick from. The doctors available from different hospitals who come under the the corresponding speciality are displayed to the user.
