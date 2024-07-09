# flight-schedule-system 

### Objective
The purpose of this project to verify the concept of Graph data structure.


### Problem
An Airport station needs a system to manage the flight schedule. The system should be able to store the cities, and store the relationship between cities flight departure and destination. Finally the system shall be able to represent the flight schedule departure and destination.


### Test Case


### Implementation
- Create a class `City` with the following attributes:
  - `name` of type `String`
- Create a class `FlightSchedule` with the following attributes:
  - `cities` of type `List<City>`.
  - `flights` of type integer 2D array to store the flight departure and destination.
- Create a class `FlightScheduleSystem` with the following attributes:
    - `flightSchedule` of type `FlightSchedule`.
    - `cities` of type `List<City>`.
    - `flights` of type integer 2D array to store the flight departure and destination.
- Create a method `addCity` in the `FlightScheduleSystem` class that takes a `City` object as a parameter and adds it to the `cities` list.
- Create a method `addFlight` in the `FlightScheduleSystem` class that takes two `City` objects as parameters and adds the flight departure and destination to the `flights` list.
- Create a method `displayFlightSchedule` in the `FlightScheduleSystem` class that displays the flight schedule departure and destination.

> The `FlightSchedule` class is actully a graph data structure, and the `City` is the vertex of the graph.

``` java
public class ParkingSystem {
    public static void main(String[] args) {
      /* add your code here */
    }

}
```


### Qualification to pass
- [ ] The code should run successfully.
- [ ] Write all required functions correctly.

