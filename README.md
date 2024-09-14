# Unit Conversion App

## Overview

The Unit Conversion App is a basic Android application designed to convert values between different units of length: meters, centimeters, millimeters, and feet. This application demonstrates the use of Kotlin and Jetpack Compose for building a simple yet functional user interface that updates conversions in real-time as users input values.

## Features

- **Real-Time Conversion**: As users enter a value in any of the input fields, the app instantly updates and displays the converted values in all other units.
- **User-Friendly Interface**: Built with Jetpack Compose, the app offers a modern, responsive design that enhances user experience.
- **Unit Selection**: Users can choose which unit to convert from and to, making it easy to switch between different measurement systems.

## Technologies Used

- **Kotlin**: A modern programming language that is officially supported for Android development. It is concise, expressive, and fully interoperable with Java.
- **Jetpack Compose**: A declarative UI toolkit for Android that simplifies UI development by allowing you to describe your UI in a composable way, using a reactive programming model.

## Features and Components

### MainActivity.kt

- Contains the primary logic for the app.
- Initializes the UI and handles user interactions.

### ConversionUtils.kt

- Houses utility functions to perform the actual conversions between meters, centimeters, millimeters, and feet.
- Provides a clean and reusable way to perform calculations.

### MainScreen.kt

- Defines the layout and user interface of the application using Jetpack Compose.
- Includes input fields for entering values, as well as text fields to display the converted values.
- Handles the logic for updating the conversion results based on user input.

## How It Works

1. **User Interaction**: The user inputs a value in one of the unit fields (meters, centimeters, millimeters, or feet).
2. **Conversion Calculation**: As the user types, the app uses functions from `ConversionUtils.kt` to convert the entered value into all other units.
3. **Real-Time Updates**: The converted values are displayed instantly in the corresponding fields, providing immediate feedback to the user.

## Code Structure

- **MainActivity.kt**: The entry point of the application where the primary logic is implemented.
- **ConversionUtils.kt**: A utility class containing methods for converting between different units of length.
- **MainScreen.kt**: A composable function that defines the app's user interface, handling user input and displaying results.

