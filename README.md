## Flight Reservation Application(REST)

### Endpoints

* User registration
```
-> /flightreservation/user/register
{
    "firstName": "X",
    "lastName": "X",
    "email": "X",
    "password": "X"
}
```
* User Login
```
-> /flightreservation/user/login
Form value -> email, password
```
* Flight Find
```
-> /flightreservation/flight/find
Form value -> from, to, departureDate
```
* Flight Reserve
```
-> /flightreservation/reservation/reserve
Form value -> flightId
```
* Make Reservation
```
-> /flightreservation/reservation/makeReservation
Form value -> flightId, passengerFirstName
     passengerLastName, passengerEmail,
     passengerPhone, others
```
* Find Reservation
```
-> flightreservation/reservation/find/1
```
* Update Reservation
```
-> flightreservation/reservation/update
{
    "id": "X",
    "checkedIn": "X",
    "numberOfBags": "X",
}
```