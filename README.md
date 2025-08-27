Objective:
Analyze airline operations data—including aircraft specifications, flight schedules,
bookings, and passenger information—to gain insights into:
● Flight performance and punctuality
● Aircraft utilization and seating efficiency
● Revenue distribution across flights and booking channels
● Passenger behavior and boarding patterns
Key Stakeholders:
Airline management, operations team, revenue management, customer service, and
data analysts.
Schema Overview
Your schema includes the following core entities:
● AIRCRAFTS_DATA: Details about aircraft (e.g., model, range).
● AIRPORTS_DATA: Information on airports with spatial coordinates and localized
names.
● FLIGHTS: Flight schedules, statuses, and references to departure/arrival airports
and aircraft.
● SEATS: Seat details per aircraft including fare conditions.
● BOOKINGS & TICKETS: Reservation details and associated ticket information.
● TICKET_FLIGHTS & BOARDING_PASSES: Junction tables linking tickets with
flights, along with fare and boarding details.
