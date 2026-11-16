# Gift of the Givers – Disaster Relief Management App

## 1. Project Overview

The Gift of the Givers Disaster Relief Management App is an Android application developed as part of a Work Integrated Learning (WIL) project.

The application aims to provide users with a convenient digital platform to interact with the Gift of the Givers Foundation. It focuses on user registration, authentication, donation submissions and accessibility.

The project uses modern Android development technologies and Firebase services to support user account management and cloud-based data storage.

## 2. Project Objectives

The main objectives of this project are:

- Develop a user-friendly Android application.
- Allow users to register and log in.
- Provide a donation form for users who wish to support relief efforts.
- Validate user information and donation details.
- Integrate Firebase Authentication.
- Use Cloud Firestore for data management.
- Provide accessibility options to improve the user experience.
- Demonstrate practical Android application development skills.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Kotlin | Main programming language |
| Android Studio | Development environment |
| Jetpack Compose | User interface development |
| Material 3 | Application design components |
| Firebase Authentication | User registration and login |
| Cloud Firestore | Cloud database |
| GitHub | Version control and source code management |
| GitHub Actions | Continuous integration workflow |

## 4. Application Features

### 4.1 User Registration and Login

- Users can register using their name, email address and password.
- Existing users can log in using their credentials.
- Email and password validation is included.
- Users can request a password reset.
- Firebase Authentication is integrated for account management.

### 4.2 Home Screen

- Provides access to the main application functionality.
- Allows users to navigate to the donation and settings screens.
- Uses a consistent visual design and colour scheme.

### 4.3 Donation Management

- Provides a donation form.
- Supports money and goods donation types.
- Allows users to enter their donation details.
- Validates required fields.
- Checks that monetary donation amounts are positive and valid.

### 4.4 Accessibility Settings

- Provides an option to increase application text size.
- Aims to improve readability and accessibility.

### 4.5 Firebase Integration

Firebase services are integrated into the application to support authentication and cloud-based data management.

Firebase Authentication handles user accounts, while Cloud Firestore is used for user profile information and configured donation data storage.

**Note:** The application is an academic prototype. It does not currently process actual online payments or issue official donation receipts.

## 5. Technologies and Development Tools

The application was developed using:

- Android Studio for application development.
- Kotlin for application logic.
- Jetpack Compose for the user interface.
- Firebase for backend services.
- GitHub for source code management.

## 6. Installation and Setup

### Requirements

- Android Studio
- Android SDK
- Kotlin support
- Firebase project
- Android emulator or physical Android device

### Step 1: Clone the Repository

Open a terminal and execute:

```bash
git clone https://github.com/LuqmaanT/GiftOfTheGivers.git
```

### Step 2: Open the Project

1. Open Android Studio.
2. Select Open.
3. Choose the cloned GiftOfTheGivers project folder.
4. Allow Gradle to synchronise the project.

### Step 3: Configure Firebase

1. Open the Firebase Console: https://console.firebase.google.com/
2. Select or create the Firebase project.
3. Register an Android application using the following package name:

```text
com.example.giftofthegivers
```

4. Download the `google-services.json` configuration file.
5. Place it inside the app directory.
6. Enable Email/Password authentication in Firebase Authentication.
7. Configure Cloud Firestore and appropriate database security rules.

### Step 4: Run the Application

1. Connect an Android device or start an emulator.
2. Select the device in Android Studio.
3. Click Run.
4. The application should launch if the project and Firebase configuration are correct.

## 7. Project Structure

The project follows a standard Android application structure.

```text
GiftOfTheGivers/
│
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       │   └── com/example/giftofthegivers/
│   │       │       └── MainActivity.kt
│   │       │
│   │       ├── res/
│   │       └── AndroidManifest.xml
│   │
│   └── build.gradle.kts
│
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

## 8. Testing

The following test scenarios are relevant to the application:

| Test Scenario | Expected Result |
|---|---|
| Register with valid details | Account is created |
| Register with invalid email | Validation or error message appears |
| Log in with correct credentials | User accesses the home screen |
| Log in with incorrect credentials | Error message appears |
| Request password reset | Password-reset request is processed |
| Submit an empty donation form | Required-field validation appears |
| Enter a negative donation amount | Validation prevents submission |
| Select goods donation | Goods details can be entered |
| Change text-size setting | Text size changes |
| Log out | User returns to the login screen |

Actual test results should be confirmed through application testing.

## 9. Development Process

The project followed an iterative development approach.

The development process included:

1. Analysing the problem and identifying project requirements.
2. Planning the application screens and navigation.
3. Designing the user interface.
4. Developing the application using Kotlin and Jetpack Compose.
5. Implementing user authentication and input validation.
6. Integrating Firebase services.
7. Reviewing the application and identifying areas for improvement.

GitHub was used to manage the source code and track project changes.

## 10. Future Improvements

Future improvements that could be introduced include:

- Secure online payment integration.
- Donation history for registered users.
- Donation confirmation and receipt generation.
- An administrator dashboard.
- Improved disaster-relief project management.
- Additional accessibility features.
- Expanded automated testing.
- Improved continuous integration and deployment.


## 12. Developer Information

**Project Name:** Gift of the Givers – Disaster Relief Management App

**Developer:** Luqmaan

**GitHub Repository:**  
https://github.com/LuqmaanT/GiftOfTheGivers

**Development Environment:** Android Studio

**Programming Language:** Kotlin

**Project Type:** Work Integrated Learning (WIL) Academic Project

---

*Developed for academic purposes as part of the Work Integrated Learning development project.*
