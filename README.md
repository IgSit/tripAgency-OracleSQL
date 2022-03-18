# Trip organization database - Oracle SQL
_In order to generate this database on your own use base_generation.sql file._

Simple project to verify basic knowledge of Oracle SQL. The project contains minimalistic
a database for trip agency to organise trips and manage reservations for them.

Most vital functionalities:
 * addReservation - adds new reservation if valid
 * modifyReservationStatus - change status of existing reservation (e.g. to 'cancelled')
 * modifyReservation - change number of places of existing reservation
 * modifyMaxNoPlaces - change maximum number of places for existing trip

All the functionalities have build-in validation of data (whether a person or trip exists,
whether it is possible to change number of places etc.).

More info about all the functions, procedures, views and triggers can be seen in description.md.