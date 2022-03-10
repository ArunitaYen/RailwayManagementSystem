# RailwayManagementSystem
the repository contains a set of command to maintain a railway reservation database system

This system helps the passengers to get information on availability of trains, tickets, booking and cancellation of tickets, enquiry on status of the booked tickets etc. So our main aim is to develop and design a database maintaining the records of trains, tickets and passengers.

Record on train involves the number of trains available on a particular date, source, destination, name etc. Record of train status consists of seat avaibility, dates of booking for each train etc. Inorder to book the tickets, a passenger has to choose the train number or name, date, source, destination. Then look into tickets and seats avaibility of that particular train and book the tickets. Once booked, ticket ID is generated along with the passenger details. When there is need for sny cancellation of the tickets, the ticket ID must be checked and cance At the same time, ticket status also gets changed correspondingly.

Entities that involved here includes User, Passenger, Train, Station, Ticket. And attributes are listed for each emtity as follows:

User:- UserID, Password, Name, Gender, Age, Mobile Number, Aadhaar Number, Address

Passenger:- Name, Address, Gender, Age, Mobile Number, Aadhaar

Train:-

Number Number, Name, Arrival Time, Departure Time, Availability of seats, Source, Destination, Seats, Fare No., Booked user, Status, Number of Passengers

Tickets:-

![ERD of reservation system](https://github.com/ArunitaYen/RailwayManagementSystem/blob/main/TrainReserve.PNG)
