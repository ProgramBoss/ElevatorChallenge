# ElevatorChallenge-master

## Overview

The Elevator Challenge project simulates the operation of an elevator system. It includes various components such as models, services, and helpers to manage elevator operations, handle passenger requests, and display the system status on the console.

## Project Structure

The project is organized into the following main directories:

- **ElevatorChallenge**: Contains the core implementation of the elevator system.
- **ElevatorChallengeTests**: Contains unit tests for the elevator system.

## Prerequisites

- .NET 8 SDK
- Visual Studio 2022 or later

## Getting Started

### Clone the Repository

### Build the Project

Open the solution in Visual Studio and build the project to restore the dependencies and compile the code.

### Run the Application

To run the application, set the `ElevatorChallenge` project as the startup project and start debugging (F5). The console application will start, and you can interact with the elevator system via the console.

## Project Details

### ElevatorChallenge

This directory contains the core implementation of the elevator system.

- **Models**: Contains the data models used in the project, such as `ElevatorStatus`, `PassengerRequest`, and `ElevatorConfiguration`.
- **Services**: Contains the service interfaces and implementations for managing elevator operations.
- **Helpers**: Contains helper classes for console output and elevator name generation.

### ElevatorChallengeTests

This directory contains unit tests for the elevator system.

- **ElevatorTests.cs**: Contains unit tests for the `Elevator` class to verify its behavior under various scenarios.

## Key Classes and Interfaces

### Models

- **ElevatorStatus**: Represents the status of an elevator, including its current floor, direction, and load.
- **PassengerRequest**: Represents a passenger request, including the origin floor, destination floor, and passenger count.
- **ElevatorConfiguration**: Represents the configuration settings for the elevator system.

### Services

- **IControlCentreService**: Interface for the control center service that manages elevator operations and passenger requests.
- **IElevatorThreadManager**: Interface for managing elevator threads.
- **IConsoleOutputHelper**: Interface for console output helper.

### Helpers

- **ConsoleOutputHelper**: Helper class for displaying information on the console.
- **ElevatorNamesHelper**: Helper class for generating elevator names based on their index.

## Running Tests

To run the unit tests, open the Test Explorer in Visual Studio and run all tests. The tests are located in the `ElevatorChallengeTests` project.
