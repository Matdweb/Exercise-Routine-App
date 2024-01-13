# Exercise Routine App 🏋️‍♂️

## Description

### Purpose
The Exercise Routine App was born out of a personal need, intending to streamline exercise routines. Its primary goals include precise time control for each exercise, voice guidance, visual aids for exercises, and easy routine customization.

### Challenges & Learnings
Developed entirely with vanilla JavaScript and CSS, this project presented challenges in asynchronous coding and working without a framework. Navigating public domain image usage and creating structured JSON files for routines added complexity. Despite the initial hurdles, the app now functions seamlessly.

## About the Project ℹ️

### Technology Stack
Built using pure vanilla JavaScript and CSS, the Exercise Routine App showcases the possibilities of fundamental web technologies.

### Logic
Asynchronous coding techniques were employed to orchestrate the app's functionality, ensuring a smooth user experience during exercises.

### Customization
The app allows effortless customization of exercise routines. By modifying the "Rutinas.txt" JSON file, users can create and tailor routines to their specific needs.

## Getting Started 🚀

To use the app:
1. Download the entire project.
2. Open the "index.html" file in your preferred web browser.
3. Customize routines by modifying the "Rutinas.txt" JSON file using the provided structure.

## Features ✨

### Routine Menu
The app presents a user-friendly menu for creating and customizing exercise routines.

### Default Routines
Two default routines, labeled 1 and 2, are included to provide users with a starting point.

### Creating New Routines
Users can easily add new routines by extending the "Rutinas.txt" JSON file with a new array structure.

### Voice Technology
Employing the Web Speech API, the app offers voice guidance, ensuring users stay informed about each exercise without needing to glance at the screen.

### NoSleep Library
To enhance the user experience, a "NoSleep" library is integrated, preventing device shutdown during app use.

## Technologies Used 🛠️

### Web Speech API
The app leverages the Web Speech API to provide audible exercise information, making the experience more immersive.

### NoSleep Library
Integration of the NoSleep library ensures uninterrupted app use, crucial for maintaining exercise routines.

## Execution Flow 🔄
Upon opening the Exercise Routine App, users are greeted with a user-friendly menu. Here's how the app flows during routine execution:

1. **Routine Selection:**
   - Users select a routine by interacting with the menu.
   - Routines can be customized by intercating with the menu.
   - You can add more routines by modifying the "Rutinas.txt" JSON file
  
     ![image](https://github.com/Matdweb/exercise-routine-app/assets/110640534/d97de504-94c4-4c75-a96d-ba9dd0a15abd)


2. **Initiating the Routine:**
   - Clicking the "Empezar" button initiates the selected routine.

3. **Exercise Information Display:**
   - During each exercise, the app displays information in a yellow header.
   - Series number, time, and the next exercise are presented in a red box.
   - Exercise guidance images are displayed at the bottom.
  
     ![image](https://github.com/Matdweb/exercise-routine-app/assets/110640534/381d2c99-66cf-4146-a460-86a24b67b23f)

4. **Time Management and Voice Guidance:**
   - Time is managed, and voice technology announces key information.
   - Users can advance to the next exercise manually.
   - The app freezes briefly to allow users to complete the current exercise.
  
     ![image](https://github.com/Matdweb/exercise-routine-app/assets/110640534/f08fea68-4526-4ee4-a9cb-c352141b8944)

5. **Routine Completion:**
   - The app guides users through the entire routine until completion.
   - An end routine message marks the conclusion of the exercise routine.
     
      ![image](https://github.com/Matdweb/exercise-routine-app/assets/110640534/deef9ab6-3c2c-49e6-acfe-e568770ddd1b)

## Learn More 📚

Explore the [Web Speech API documentation](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) for more details on its implementation.
