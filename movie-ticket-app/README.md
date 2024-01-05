* Movie Ticket Booking Application
* In-Memory App, no need to integrate the database.

## Requirements

* There exist multiple cinemas in the city and the cinema has multiple halls.
* Each movie in the cinema can have multiple shows, however, one hall will only one show at a time.
* The cinema displays all the available show times of a movie.
* Users can search movies based on the following four criteria: title, language, genre and release date.
* Users can make a booking at any cinema hall at the available show time.
* The booking can either be made by the customer online or via a walk-in by the ticket agent.
* Online customers can only pay using a credit card, while walk-in customers can pay using cash or credit card through the ticket agents.
* Users can select multiple available seats for a show from a given seating arrangement.
* Each Seat has a fixed cost and there are three types of seats: silver, gold and platinum.
* There can only be one ticket allocated per seat.
* No Two customers should be able to reserve the same seat.
* The admin can perform the following actions on the show times and the movie
  * Add a show.
  * Delete a show.
  * Update a show.
  * Add a movie.
  * Delete a movie.
* The system should be able to differentiate between available and booked seats.
* The system should generate a notification for the following cases:
  * A new movie has been released.
  * A booking has been made.
  * A booking has been cancelled.