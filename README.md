# Graph algorithms for finding the Cheapest Flight

Project done for the "Algorithms laboratory" course, Bachelor Degree in Computer Science at University of Palermo.
Team: Andrea Spinelli, Marco Valenti, Raffaele Terracino
Language: C++

## Problem statement
The goal is to design a graph algorithms to solve the following problem.

Passionate about modern artwork, Mario has decided he would like to visit Ney York City.
Mario lives in Palermo and would like to find the cheapest flight or flights that would get him to New York.
He knows that a direct flight from Palermo to New York, if it existed, would be incredibly expensive; therefore, he is willing to
tolerate a number of layovers. However, there are many airlines offering flights between different
cities, which makes it very difficult for Mario to find the cheapest way to get to New York!
Can you write a schedule to help Mario plan his route?
You will be provided with a list of cities between Palermo and New York, including both. You will also be provided with a list of
flights between the city pairs, and the associated cost for each flight, including taxes. There will never be a flight from Palermo to New York:
Mario has already discarded those flights, deeming them a waste of time and money. Keep in mind, however, that there may be more
flights between two cities, as Mario is considering flights from all airlines.
Finally, you will be presented with a number of queries. Each query is a single integer indicating the maximum number of stopovers
that Mario is willing to tolerate. For each query, your program must calculate the minimum total cost of flights that
would take Mario from Palermo to New York with no more than a certain number of required stopovers.

## Input
The first line of the input contains a single number indicating the number of scenarios to be processed.
A blank line precedes each scenario.
Each scenario begins with a number $N\geq2$, the number of cities, followed by $N$ lines containing the names of the cities.
A city name is a string of uppercase and lowercase letters.
Next, a number $M\get0$, the number of available flights, is provided, followed by M rows describing the flights.
Each flight is described by the departure city, the destination city, and an integer representing the cost in euros.
The last row begins with $Q\get1$ the number of queries, followed by 𝑄 numbers indicating the maximum number of stopovers.

## Ouput
For each scenario, your program should return the scenario number, followed by the minimum total cost of flights
for each query. If no flights can satisfy a query, write "No flights." Insert a blank line between the scenarios.
