# SpringDataJPAWithBoot

Test APIs
=========================================================================

Creating New Record:
/booking/create?psngrName=shadab&departure=Noida&destination=Pune create a new booking with an auto-generated.
For Example:
http://localhost:8181/booking/create?psngrName=Arnav&destination=USA&departure=Delhi

Reading a Record:
/booking/read?bookingId=[bookingId]: Read the booking with the passed bookingId.
For Example:
http://localhost:8181/booking/read?bookingId=1
Updating a Record:
/booking/update?bookingId=[bookingId]&psngrName=Sweety: Update the booking for a given booking id.
For Example:
http://localhost:8181/booking/update?bookingId=5&psngrName=Suresh

Deleting a Record:
/booking/delete? bookingId=[bookingId]: Delete a booking for given booking id.
For Example:
http://localhost:8181/booking/delete?bookingId=5
booking #5 deleted successfully
