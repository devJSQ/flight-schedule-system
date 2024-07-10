# flight-schedule-system 

### Objective
The purpose of this project is to verify the concept of Graph data structure.


### Problem
An Airport company needs a system to manage the flight schedule. The system should be able to store the cities and the relationship between cities flight departures and destinations. Finally, the system shall be able to represent the flight schedule departure and destination.


### Test Case
``` java
class Main {
    public static void main(String args[]){
        FlightSchedule flightSchedule = new FlightSchedule();

        flightSchedule.addCity(new City("Riyadh"));
        flightSchedule.addCity(new City("Toktyo"));
        flightSchedule.addCity(new City("Boston"));
        flightSchedule.addCity(new City("Kyoto"));
        flightSchedule.addCity(new City("Jeddah"));

        flightSchedule.addFlight(0, 1);
        flightSchedule.addFlight(0, 2);
        flightSchedule.addFlight(1, 3);
        flightSchedule.addFlight(1, 4);
        flightSchedule.addFlight(2, 3);
        flightSchedule.addFlight(3, 4);

        flightSchedule.printFlights();
    }
}
```
#### Output
```
Riyadh -> Toktyo
Riyadh -> Boston
Toktyo -> Kyoto
Toktyo -> Jeddah
Boston -> Kyoto
Kyoto -> Jeddah
```

### Implementation
- Create a class `City` with the following attributes:
    - `name` of type `String`
- Create a class `FlightSchedule` with the following attributes:
    - `cities` of type `ArrayList<City>` with initializer.
    - `flights` of type integer 2D array with a size of five, to store the flight departure and destination.
    - Create a method `addCity` in the `FlightScheduleSystem` class that takes a `City` object as a parameter and adds it to the `cities` list.
    - Create a method `addFlight` in the `FlightScheduleSystem` class that takes two `City` objects as parameters and adds the flight departure and destination to the `flights` list.
    - Create a method `displayFlightSchedule` in the `FlightScheduleSystem` class that displays the flight schedule departure and destination.

### Note
> The `FlightSchedule` class is actually a graph data structure, and the `City` is the vertex of the graph.
> You're required to import java.util.ArrayList to store the cities.



### Qualification to pass
- [ ] The code should run successfully.
- [ ] Write all required functions correctly `addCity()` `addFlight()`, and `displayFlightSchedule()`.
- [ ] The output should match the test case.
- [ ] Use the Graph data structure to solve the problem.

