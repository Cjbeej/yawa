# Travel Fare Calculator

## Description
This program calculates the total fare based on the travel distance and number of passengers.

## Version 1 - Original code without input validation
- Input: Passenger name, distance in kilometers, and number of passengers.
- Process: Multiplies the distance by the fare rate of PHP 14 and the number of passengers.
- Output: Displays the passenger's name and total fare rounded to two decimal places.
- Does not include input validation.

## Version 2 - Code with input validation
- Input: Passenger name, travel distance in kilometers, and number of passengers.
- Process: Checks that the passenger name is not empty, the distance is a number greater than 0, and the number of passengers is a positive whole number. If an input is invalid, the program displays an error message and asks the user to re-enter it.
- Output: Displays the passenger's name and total fare in PHP, rounded to two decimal places.
- Validation: Prevents empty names, invalid distances, and invalid passenger counts.
