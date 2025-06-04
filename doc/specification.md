Project Specification & Database Design

THE GUIDELINE OF THIS PROJECT ;

●	Requires PHP to process logic (e.g., user input, decision-making)
●	Uses MariaDB to read/write meaningful data
●	Produces dynamic content on the webpage



1. Demo Scenario Overview
●	A user fills out a Amount($), Date, Category, Notes.
●	The system processes the input, saves it , and input into the booking to the database.
●	A save button displays in the log box.
●	An admin/demo page shows a list of all saved expenses.


2. Planned URL Endpoints

URL Path	Method	HTTP Variables	Session Variables	Database Operations
/booking_form.php	GET	-	-	-
/submit_booking.php	POST	amount, date, category, notes.
/confirmation.php	GET	booking_id	None	Fetch booking by ID
/view_bookings.php	GET	-	None	Fetch all bookings
