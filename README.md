# Navigation App - Lab 8
## Student Information
- **Name:** April Paz
- **Student ID:** N01327224
- **Course:** CPAN 213 - Cross-Platform Mobile Application Development
- **Lab:** Lab 8 Building Multi-Screen Navigation Systems
Date: November 20, 2025

## Project Description
This React Native application demonstrates professional multi-screen navigation systems using React Navigation. The app features both Stack and Tab navigators with parameter passing, custom headers, and authentication-ready navigation flows.

## Features Implemented
Stack Navigator with 3 screens (Home, Details, Profile)

Bottom Tab Navigator with 3 tabs (Home, Search, Settings)

Parameter passing between screens

Custom header styling and dynamic titles

Navigation actions (navigate, goBack, setParams)

Search functionality with state management

Settings screen with toggle switches

## Technologies Used
React Native 0.72+

React Navigation 6.x

@react-navigation/stack

@react-navigation/bottom-tabs

react-native-vector-icons

react-native-gesture-handler

react-native-safe-area-context

## Installation
Clone the repository

Install dependencies: npm install

Install iOS pods (macOS only): cd ios && pod install

Run on Android: npx react-native run-android

Run on iOS: npx react-native run-ios

## Project Structure
text
src/
├── navigation/
│   ├── StackNavigator.js
│   └── TabNavigator.js
├── screens/
│   ├── HomeScreen.js
│   ├── DetailsScreen.js
│   ├── ProfileScreen.js
│   ├── SearchScreen.js
│   └── SettingsScreen.js
└── App.js
Navigation Hierarchy
text
NavigationContainer
└── TabNavigator
    ├── Home Tab (StackNavigator)
    │   ├── HomeScreen
    │   ├── DetailsScreen
    │   └── ProfileScreen
    ├── Search Tab
    │   └── SearchScreen
    └── Settings Tab
        └── SettingsScreen

## Key Navigation Features
- Stack Navigation: Push/pop screens with back button support
- Tab Navigation: Persistent bottom tabs with icons
- Parameter Passing: Object parameters between Home and Details screens
- Dynamic Headers: Title updates based on route parameters
- Navigation Actions: navigate(), goBack(), setParams()

## Testing Checklist
- Stack navigation between Home, Details, and Profile
- Parameter display and updates in Details screen
- Tab navigation with all 3 tabs functional
- Custom header styling applied
- Back navigation working correctly
- Search functionality with state
- Settings toggles working
