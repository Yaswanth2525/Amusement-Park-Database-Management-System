# Amusement Park Database Management System


## Project Overview

The Amusement Park Database Management System provides comprehensive data management for amusement parks. It tracks:

- Registered users and their interactions with the park.
- Feedback on specific rides.
- Details about various park rides, including land and water rides.
- Payment details for each trip.
- Restaurant information within the park.

---

## Features

1. **User Registration**
2. **Ride Management**
3. **Feedback System**
4. **Payment Tracking**
5. **Restaurant Details**

---

## Database Structure

### Key Entities:

- **Customer**
- **Ride**
- **Amusement_Park**
- **Restaurant**
- **Feedback**
- **Payment**
- **Ticket**

---

## Normalization and Dependencies

The database is designed following BCNF (Boyce-Codd Normal Form), ensuring no partial or transitive dependencies. Each table's functional dependencies ensure data consistency and integrity. For example:

- **Customer**: `Email_ID -> Name, DOB`
- **Ride**: `Ride_ID -> Ride_Name, Type, Cost`
- **Payment**: `Payment_ID -> Status, Grand_Total, User_ID`

---


## Conclusion

This is proper system that handles required features in th context of amusement park database
