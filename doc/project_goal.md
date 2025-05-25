OSP DRAFT

Project title: Study Room Booking System

High Level Functionality: A website/system where students can select a room and timeslot to use a study room. A booking based website using PHP that integrates a database using MariaDB with Raspberry Pi Zero 2 as the host and Database.

Example Scenarios:
User: Student/library user
What the user wants to do: Get a private study room in the library.
how the request message starts from the user: User selects a room that is available and selects the time slot for their usage.

how it may be processed: The system will occupy the time slot based on the user’s request and make the room unavailable to others during the specified time and finally how the system responds: The system will return a success message and the room will be reserved by the user. The user can now use the study room without anyone entering.

USERS -> Students
What do USERS do? -> interact with the website to book a room choosing time slots.

Pseudocode of the process:
Start
system-> “Would you like to book a room?”
user-> “yes”
system-> “choose a time slot from 6 am to 10 pm”
User-> chooses time slot
system-> “Please enter name, student ID and department.”
user -> enters information
system-> reiterates the booking information for confirmation.
system-> “Please confirm booking information”
user-> confirm
system-> saves data into database including time slot, name, student ID and department.
//user can look up booking time by searching name or student ID// 
End
