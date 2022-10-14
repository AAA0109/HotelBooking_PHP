**Database design** <br>
There are three tables which include:
- customer
- booking
- reservation

Booking has info of reservation and customer via foreign key. 
Booking and reservation has one-to-one relationship. This means,
reservation must extends booking when designing the models. <br>

**Model design** <br>
`class Booking { }` <br>
`class Reservation extends Booking { }` <br>
