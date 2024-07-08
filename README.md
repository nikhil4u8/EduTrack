# EduMonitor

EduTrack is a daily Android app designed to help students forecast their GPA, manage their academic scores, and keep track of their attendance.

## Authored by Nikhil Gupta

## Why EduMonitor

In institutions like IIT Ropar and numerous other colleges, students typically receive their GPA only after final exams, leaving them with no opportunity to improve their scores mid-term. EduTrack offers a solution by allowing students to predict their GPA from the very first test, giving them insight into their academic standing and enabling them to adjust their efforts accordingly. Additionally, the app features an attendance management system that monitors attendance in real-time and informs students about how many classes they can miss or need to attend to maintain satisfactory attendance.

## Getting Started

To start using this project on your local machine, simply clone or download it, set up the [Firebase Console](https://firebase.google.com/docs/android/setup), open the project in Android Studio, and run it on any Android device or emulator.

### Prerequisites

A Google account is required to set up Firebase.

## Application Usage

On the initial screen, users are prompted to enter basic information (College, Batch, and Branch) to automatically fetch subjects for selected colleges. Users can then sign up or sign in using Firebase Auth UI. They also have the option to add or delete their own subjects. The app includes feedback and sharing options, as well as a reset feature to clear all data and log out. Note that attendance data and scores are stored locally, with no data being uploaded. The source code is available for verification. Authentication is managed using Google's Auth UI, ensuring that passwords are secure and not accessible by the developer.

## Built with

* [Firebase](https://firebase.google.com/) - Used for a large number of features.
* [Maven](https://dl.google.com/dl/android/maven2/index.html) - Dependency Management.
* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - For Pie Charts used in the app.

## Versioning

This is EduTrack v1.24 Pilot-3. The numbers to the left of the decimal point indicate major releases, those to the right represent significant commits, and "Pilot" denotes the target user group for this release.

## Acknowledgements
* I am thankful to PhilJay MP Android Chart for the awesome graphing library.
* I am very greatful to the person who designed the icon, I searched a lot for his name but in vain.
