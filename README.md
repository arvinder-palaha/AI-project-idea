<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Plane Boarding AI Scheduler

## Summary

This project would provide an improved schedule for boarding an aircraft, minimising the time to board while keeping groups and families together.
Input data would be collected at check in, with a schedule provided once all have checked in, for instance at the gate.


## Background

Boarding an aircraft very often involves long queueing times, waiting in the aisle to reach a seat while the passenger in front is stowing luggage.
A more efficient boarding schedule would cut down boarding time, hopefully reducing passenger frustration and perhaps improving turn around time for aircraft.

Such an improvement in boarding could improve one common aspect of air travel, and would be personally satisfying in optimising this process.

## How is it used?

This project would be used by a flight carrier's check in computers, providing a solution or schedule to be used at the boarding date.
The solution would be a sequence of passengers that would board the aircraft in turn.
The user(s) of this system would be the flight staff responsible for passenger boarding.

## Data sources and AI methods

The input data would come from the check in information of passengers arriving for a flight.
Once all have checked in, a schedule would be generated and applied at the boarding date.

The training data would come from either historical check in records and boarding data (if it exists) or recording checkins and boarding to collect a training data set.

The AI methods would be trained to produce a boarding schedule, or sequence of passengers, that would take the shortest time to board without splitting groups.

## Challenges

The solution from this project assumes that passengers would cooperate with the boarding schedule.
This is not a given, and more likely than not would be difficult to get.

## What next?

This project could potentially be applied to any situation involving the movement of people through some sort of bottleneck or constricted entryway.

## Acknowledgments

* Video by CGP Grey: https://www.youtube.com/watch?v=oAHbLRjF0vo
