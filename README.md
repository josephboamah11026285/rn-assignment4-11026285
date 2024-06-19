# rn-assignment4-11026285

# React Native Assignment 4 - Mobile Application Development

This repository contains my implementation of Assignment 4 for DCIT202 Mobile Application Development.

## Project Overview

This mobile application is designed to replicate the UI mockup provided for Assignment 4. It includes features such as a login screen, home screen displaying user details, and sections for popular and featured job listings. The application is styled to closely match the provided UI design using custom components throughout.

## Components Usage

### Login Screen

The login screen allows users to enter their credentials. Upon pressing the login button, the application validates the input and navigates to the home screen if the login is successful. The user's name and email are passed to the home screen upon login.

### Home Screen

The home screen displays the user's name and email, retrieved from the login screen. It provides navigation to different sections of the application, including the popular jobs and featured jobs sections.

### Popular Jobs Component

This component renders a list of popular job cards, each displaying job details such as title, company, salary, location, and an image. The component is designed to accept props for job details, making it reusable for displaying different job listings dynamically.

### Featured Jobs Component

Similar to the popular jobs component, the featured jobs component displays a list of featured job cards. It uses props to render job details such as title, company, salary, location, and an image. This component enhances the user experience by showcasing highlighted job opportunities.

### Custom Components

- **Navigation Bar**: A custom navigation component is implemented for seamless navigation between screens.
- **Job Card Component**: A reusable component styled to display job details in a card format with consistent design across the application.
- **Styled Buttons**: Custom buttons with specific styling are used for interactive elements throughout the app, ensuring a cohesive user interface.

## Screenshots

### Login Screen
![Login Screen](C:\Users\joey\Desktop\rn-assignment4-11026285\assignment4\assets\IMG_3715.PNG)

### Home Screen
![Home Screen](C:\Users\joey\Desktop\rn-assignment4-11026285\assignment4\assets\IMG_3715.PNG)

## Installation Instructions

To run this application locally, follow these steps:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your-username/rn-assignment4-ID.git
   ```
2. Navigate into the project directory:
   ```
   cd rn-assignment4-ID
   ```
3. Install dependencies using npm or yarn:
   ```
   npm install
   ```
   or
   ```
   yarn install
   ```
4. Run the application on a simulator or device:
   ```
   npm run start
   ```
   This command will start the Metro bundler and provide options to launch the app on iOS or Android simulators, or on a connected device.

## Technologies Used

- **React Native**: Framework for building native mobile applications using JavaScript and React.
- **Expo**: Development toolchain and platform for building and deploying React Native apps.
- **React Navigation**: Library for handling navigation and routing in React Native apps.
- **Custom Components**: Utilized to maintain consistent styling and functionality across different screens and components.

