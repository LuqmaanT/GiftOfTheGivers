# Gift of the Givers – Release Notes

## Version 1.0 – Development Prototype

### Project Overview
This release represents the development of the Gift of the Givers Disaster Relief Management Android application as part of the Work Integrated Learning project.

The application provides a mobile platform with user authentication, donation-related functionality and accessibility options.

### Features Included

**1. User Interface**
- Developed the application interface using Kotlin and Jetpack Compose.
- Created a consistent visual theme using navy blue, blue and light background colours.
- Implemented separate Login, Home, Donations and Settings screens.
- Added navigation between the main application screens.

**2. User Authentication**
- Integrated Firebase Authentication.
- Added user registration using email and password.
- Implemented login functionality.
- Added email and password validation.
- Included a password-reset feature.
- Added logout functionality.

**3. User Profile Management**
- Integrated Cloud Firestore for user profile information.
- Added functionality to create and update user profile records.

**4. Donation Form**
- Developed a donation form.
- Added support for money and goods donation types.
- Implemented donor name validation.
- Added validation for required donation details.
- Included positive numeric amount validation for monetary donations.

**5. Accessibility**
- Added a larger-text accessibility option.
- Improved the application's readability and usability.

### Technical Improvements
- Used Jetpack Compose for modern Android UI development.
- Integrated Firebase services.
- Implemented application state management using Compose.
- Added form validation and user feedback.
- Organised the application using Kotlin functions and reusable UI components.

### Known Limitations
- Online payment processing is not included.
- Official donation receipts are not generated.
- Administrative disaster-relief management functionality requires further development.
- Accessibility settings may not persist after the application is closed.
- Firebase database functionality must be tested with the correct configuration and security rules.

### Future Development
Future versions may include:
- Donation history.
- Secure online payment integration.
- Donation confirmation and receipt generation.
- Administrator functionality.
- Improved accessibility options.
- Additional automated testing.
- Expanded disaster-relief management functionality.

---

**Project:** Gift of the Givers Disaster Relief Management App  
**Version:** 1.0  
**Platform:** Android  
**Language:** Kotlin  
**Framework:** Jetpack Compose  
**Backend Services:** Firebase Authentication and Cloud Firestore
