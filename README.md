### RobotAPI Solution
This repository contains Web API (RobotAPI) – a RESTful API for managing robot commands.
The Web API provides a set of endpoints for controlling a robot.

## Prerequisites
Make sure you have the following installed:

Visual Studio or Visual Studio Code

.NET SDK (Version 8.0 or higher)

Postman or any other API client (optional for testing endpoints manually)

## How to Run
Clone the repository and install dependencies
1. Create a folder in File Explorer and open Git Bash inside it
2. Clone the repository using the command:
git clone https://github.com/Bathina-Tejaswi/RobotAPI.git

## Open the project in Visual Studio
Run the RobotAPI project
1. By default, the API will run on:
https://localhost:7197 (or another port if configured)
2. Alternatively, you can test the API using Postman

## Commands
PLACE X,Y,FACING – Places the robot at the specified position and facing direction

MOVE – Moves the robot forward in the current direction

LEFT – Rotates the robot 90 degrees counterclockwise

RIGHT – Rotates the robot 90 degrees clockwise

REPORT – Outputs the robot's current position and facing direction
