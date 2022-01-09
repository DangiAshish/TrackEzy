# Android-Study-Jams
TrackEzy
Problem Statement:
In today's world, it's a piece of cake to perform every task at their fingertips with the advancement in new-age technology.
Thereby we present our app 'TrackEzy'. It is an Android application used for tracking the attendance of organizations like schools, offices, etc. The app helps the user by switching from the traditional way of keeping records, maintaining the attendance reports of students/employees to digital technology. 
Proposed Solution:
TrackEzy helps the users to keep track of the students’/employees attendance. The user can add the sector or subjects for which they want to track attendance the data thereby gets saved in the room database. The sectors can also be updated by deleting the existing and adding new ones. The new students are to be added to the respective sectors. Using the checkbox functionality the members present are recorded and the total number of present and absent members are displayed accordingly.
Screenshots:



Functionality and Concepts used:
An interactive and user-friendly interface is developed with the help of material design views.
●	Constraint Layout:  It allows you to position and size widgets in a flexible way.
●	Linear Layout:  It aligns all children in a single direction, vertically or horizontally oriented.
●	Simple & Easy Views Design: TextViews with hints are used to instruct the user where they can write the appropriate information. Buttons are used to perform specific tasks. 
●	JetPack Navigation: JetPack components are used for bottom navigation is used to switch between fragments. Check box functionality is used to keep track of the present members.
●	RecyclerView: To present the list of sectors and the list of students recycler view is used
●	LiveData & Room Database: LiveData is used to update changes in the number of sectors received from their mobile in real-time and update it to local databases using Room. Coordinates are then updated in the fragments where records of sectors are updated and users can update the information accordingly.
●	Coroutines: Many coroutines can run on a single thread due to support for suspension, which doesn't block the thread where the coroutine is running. Suspending saves memory over blocking while supporting many concurrent operations. In this app, they are used for the database.



Application Link:https://drive.google.com/file/d/1Kqd4yzpu8W8kRFhaAvccGwoQwaGilmrs/view?usp=sharing


Future Scope:
1.	Provision for students/employees to update the reason for being absent.
2.	Generation monthly and yearly reports of attendance.
3.	Keep records of daily attendance.
4.	Provision to get pdf form to print the report

