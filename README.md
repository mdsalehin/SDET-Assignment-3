## Overview  
This project demonstrates performance testing of the Restful Booker API using JMeter, covering both load and stress testing.

## Booking Service API Features
-  Login (/auth)
- Create a booking (/booking)
- Search the booking (/booking/{booking_id})

## Test Flow / Steps
- Login → Create Booking → Search Booking.
- Gaussian timer simulates User think time.

## Summary
This assignment demonstrates performance and load testing on the Restful Booker API. The test scenario involves 120,000 users performing login, creating bookings, and searching for bookings over a 12-hour period. The goal is to evaluate system throughput, identify bottlenecks, and ensure the server handles high loads efficiently.

## Scenario / Load Details
- Users: 120,000 over 12 hours.
- Load Test: gradually increasing users.
- Stress Test: fixed time, increasing number of users.

## Technical Scope:
- Apache JMeter.
- Gaussian Random Timer.
- JSON Extractors for token & booking ID.
- HTML report generation.
- Excel reporting for Load Test & Stress Test.

## API Documentation:
- https://restful-booker.herokuapp.com/apidoc

## How to Run
jmeter -n -t script.jmx -r -l script.jtl  // run on all servers.




