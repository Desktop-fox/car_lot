# 08 TypeScript and OOP: Vehicle Builder

## Project Overview

The Vehicle Builder is a command-line application written in TypeScript that allows users to create, select, and interact with different types of vehicles. This project has been extended to support three types of vehicles:

- **Car**
- **Truck**
- **Motorbike**

Each vehicle type gathers unique details:
- **Car:** Standard vehicle with basic properties.
- **Truck:** Includes a towing capacity property and a unique **tow** action.
- **Motorbike:** Prompts for extra wheel details and offers a unique **wheelie** action.

The application utilizes [Inquirer](https://www.npmjs.com/package/inquirer) to collect user input and loops continuously until the user chooses to exit.

## Features

- **Vehicle Creation:**  
  Choose to create a new vehicle by selecting one of the three types. Each type prompts for specific details.

- **Select Existing Vehicle:**  
  Pick an existing vehicle from a list to perform actions on it.

- **Vehicle Actions:**  
  Once a vehicle is selected, you can:
  - Print details
  - Start, accelerate, decelerate, and stop the vehicle
  - Turn left/right and reverse
  - **Truck:** Tow another vehicle (only available for trucks)
  - **Motorbike:** Perform a wheelie (only available for motorbikes)

- **Continuous Loop:**  
  After every action, the application returns to the actions menu until you decide to exit.

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
