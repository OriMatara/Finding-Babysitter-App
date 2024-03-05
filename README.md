# Babysitter Finder App

## Overview

The Babysitter App is an Android application developed using Java and Firebase to efficiently connect users with local babysitters based on their proximity. This project aims to streamline the process of finding and booking babysitting services while ensuring the authenticity and verification of babysitters through a comprehensive user registration and validation system.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Features

- **User Authentication:** Secure user registration and login system using Firebase Authentication.
- **User Verification:** Mandatory profile verification process, including selfie, user ID, and Facebook link.
- **Location Services:** Utilizes Android Location API to determine the user's location for proximity-based babysitter suggestions.
- **Firebase Realtime Database:** Stores and retrieves user profiles and babysitter data.
- **Babysitter List:** Displays a list of available babysitters with relevant details.
- **Search and Filter:** Enables users to search and filter babysitters based on preferences.

## pictures
![sign in](https://github.com/OriMatara/Babysitter-Finder-App/blob/3154fc787a9696e2e099226429191a71c2c44a1c/pictures/1sign%20in.png)
![sign up]([relative/path/to/image.jpg](https://github.com/OriMatara/Babysitter-Finder-App/blob/035d07a3cc83f0af1abbaa8f35c4cff6279c7978/pictures/2sign%20up.png))


## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/babysitter-app.git
   cd babysitter-app
   ```

2. **Set up Firebase:**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Add an Android app to your project and download the `google-services.json` file.
   - Place the `google-services.json` file in the `app` directory.

3. **Build and Run:**
   - Open the project in Android Studio.
   - Build and run the app on an emulator or a physical device.

## Usage

1. **User Registration:**
   - Sign up with a valid email and password.
   - Complete the mandatory profile verification process.

2. **Browsing Babysitters:**
   - Explore the list of available babysitters.
   - Use search and filter options to find suitable babysitters.

3. **Booking a Babysitter:**
   - Connect with babysitters through the contact information.
