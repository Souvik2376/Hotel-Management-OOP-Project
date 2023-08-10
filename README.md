# Hotel-Management-OOP-Project

This hotel management application may be used to manage tasks including maintaining client information, reserving rooms of four distinct types, ordering meals for specific rooms, unreserving rooms, and displaying the bill. Additionally, it may be utilised to view various accommodation amenities and room availability. The menu-driven programme runs till the user closes it. In order to preserve the existing information when we resume the programme, file handling has been utilised to keep the present status of the hotel (client details, booked rooms, and food orders) in a file after the programme leaves. When the programme is restarted, it scans the file to determine the hotel's prior state. A separate thread has been used to write the file. The program reads the file .when it restarts to know the previous status of the hotel. Writing of file has been done in a
separate thread as it can be done parallely. User defined exception is thrown if the user
tries to book an already allotted room. Exception handling is properly done to deal with any
kind of unexpected exception.

