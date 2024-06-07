# Workout Logging Mini Project

## Objective
Build a workout logging system where users can log their workouts, view history, and see graphical representations of their progress.

## Features to Implement
1. **User Registration and Login:**
   - Create user accounts with registration and authentication.
2. **Workout Logging:**
   - Allow users to log details of their workouts.
3. **Progress Visualisation:**
   - Display graphical views of workout progress.
4. **History Tracking:**
   - Track and display workout history.

## Description
This project aims to build a workout logging system where users can log their workouts, view history, and see graphical representations of their progress.

**Aspects to Consider:**

- **Schema Design:**
  - Think about the data you need to capture for each workout (e.g., exercise type, duration, sets, reps).
  - Consider how to store and retrieve historical data for progress tracking.

- **React App Design:**
  - Design components for workout logging, viewing past workouts, and displaying progress graphs.
  - Use a graphing library to visualise workout progress over time.

- **Best Practices:**
  - Ensure a smooth user experience with easy navigation and quick logging capabilities.
  - Implement robust error handling and validation for workout data.
  - Make sure the app is optimised for performance, especially when dealing with large datasets.

## Technical Requirements
- **Backend:** Node.js with Express
- **Database:** Supabase
- **Frontend:** React
- **Graphing Library:** Chart.js or similar

## Steps to Build
1. **Set up the project:**
   - Initialise a new Node.js project.
   - Set up Supabase and connect it to the project.
2. **Authentication:**
   - Implement user registration and login with Supabase Auth.
3. **Workout Logging API:**
   - Create endpoints to add, update, delete, and fetch workout logs.
4. **Frontend:**
   - Build React components for registration, login, workout logging, and progress visualisation.
   - Use a graphing library to visualise progress.
