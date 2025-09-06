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
- jmeter -n -t script.jmx -r -l script.jtl  // run on all servers.
## Attachments:
- Load Test Report (Excel)
<img width="1166" height="606" alt="image" src="https://github.com/user-attachments/assets/88eca2b8-d2d3-4aa9-ac59-a5080f989b9a" />

- Stress Test Report (Excel)
<img width="1044" height="518" alt="image" src="https://github.com/user-attachments/assets/81c2b862-38e7-4d33-8872-192dc8b8b7f0" />

## Test Report (HTML)
<img width="1647" height="667" alt="image" src="https://github.com/user-attachments/assets/851211df-6ce4-4a72-8519-be2af7712100" />
<img width="1630" height="623" alt="image" src="https://github.com/user-attachments/assets/f896b2d8-a39e-4c3b-93d6-83403db1e75e" />








