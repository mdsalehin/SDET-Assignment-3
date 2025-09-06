## Overview

## This project demonstrates performance testing of the Restful Booker API using JMeter.

## This project demonstrates performance testing and load testing of the Restful Booker API using JMeter.

## Scenario: 120,000 users over 12 hours perform:

-  Login (/auth)
- Create a booking (/booking)
- Search the booking (/booking/{booking_id})
## Summary
 
This assignment demonstrates performance and load testing on the Restful Booker API. The test scenario involves 120,000 users performing login, creating bookings, and searching for bookings over a 12-hour period. The goal is to evaluate system throughput, identify bottlenecks, and ensure the server handles high loads efficiently.

## Technical Scope:
The assignment uses Apache JMeter for performance testing, including features such as Gaussian Random Timers to simulate think time, JSON Extractors for dynamic data like tokens and booking IDs, and HTML report generation. Test results are also documented in an Excel file for both load and stress tests.


## How to Run
jmeter -n -t script.jmx -r -l script.jtl  // run on all servers


