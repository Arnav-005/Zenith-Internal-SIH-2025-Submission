## Tasks Accomplished

- **Firebase Backend:** Successfully set up Firebase Authentication and Firestore for user and data management.
- **User Registration & Roles:** Implemented a registration and login system for both "Student" and "Teacher" roles.
- **Bluetooth Proximity Detection:** Built and tested the core logic for a teacher's device to scan and discover nearby student devices.
- **Data Transmission:** Securely fetching student data from Firebase to be transmitted via Bluetooth.
- **UI:** Designed a complete, professional user interface for all major application screens.

## Technology Stack

- **Flutter:** For cross-platform (iOS and Android) mobile app development.
- **Dart:** The programming language used for Flutter.
- **Firebase:** Used as the backend-as-a-service for: Authentication, Firestore, Storage.
    

## Key Features

- **Feature 1: Dual-Layered Security:** Combines secure biometric login to verify the user with Bluetooth proximity detection to verify physical presence, eliminating proxy attendance.
- **Feature 2: Real-time Analytics Dashboard:** An integrated screen for teachers to view class attendance trends, daily absentee counts, and a dynamically generated list of at-risk students.
- **Feature 3: Automated & Instantaneous Marking:** A seamless, single-tap process for teachers to initiate attendance, which is automatically marked for all present and logged-in students in seconds.

## Local Setup Instructions

**Prerequisites:**
- Flutter SDK (Version 3.32.0)
- Android Studio or VS Code
- An active Firebase project.

**Steps:**
1. Clone the repository:
   `git clone [YOUR_FINAL_REPO_LINK]`
2. Navigate to the project directory:
   `cd Zenith-SIH-2025-Submission/code`
3. Install dependencies:
   `flutter pub get`
4. Run the app:
   `flutter run`
