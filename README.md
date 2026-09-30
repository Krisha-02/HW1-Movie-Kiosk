# Movie Theater Ticket Kiosk
   This is a toy self-service kiosk for a movie theater. Customers can browse movies and showtimes, choose an available seat, and buy a ticket. The system shows a confirmation and prevents the same seat from being sold twice.


## Use Case: Purchase Ticket
Primary Actor:Customer

Precondition:The kiosk is running and at least one showtime has available seats.

Main Steps:
1. Customer selects a movie and showtime.
2. Kiosk displays the available seats.
3. Customer selects an available seat.
4. Kiosk confirms the seat is still available and holds it.
5. Customer enters payment information.
6. Kiosk processes the payment.
7. System issues the ticket and marks the seat as sold.
8. Kiosk displays a purchase confirmation.

Postcondition:The ticket is issued, the seat is marked sold, and it cannot be sold again.
