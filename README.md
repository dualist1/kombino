Kombino
Kombino is a Flutter-based mobile application that allows users to create and manage their digital wardrobe, generate outfit combinations, and plan their weekly outfits.
Features

User registration and login using Firebase Authentication.
Create a digital wardrobe by uploading clothing item photos and categorizing them.
Generate automatic outfit combinations (placeholder algorithm).
Save favorite combinations.
Plan weekly outfits.

Technologies

Flutter: Cross-platform mobile UI framework.
Firebase Authentication: For user management.
Cloud Firestore: For storing clothing item data.
Firebase Storage: For storing clothing images.

Setup Instructions

Clone the repository:
git clone <repository-url>
cd kombino


Install dependencies:
flutter pub get


Set up Firebase:

Create a Firebase project at Firebase Console.
Add an Android/iOS app to your Firebase project.
Download the google-services.json (Android) or GoogleService-Info.plist (iOS) and place them in the appropriate project directories.
Enable Firebase Authentication (Email/Password) and Firestore in the Firebase Console.
Set up Firebase Storage for image uploads.


Run the app:
flutter run



Project Structure

lib/main.dart: Entry point of the application.
lib/screens/login_screen.dart: User login interface.
lib/screens/home_screen.dart: Main navigation hub.
lib/screens/wardrobe_screen.dart: Manage and view clothing items.
lib/screens/combination_screen.dart: Generate outfit combinations.
lib/screens/planner_screen.dart: Plan weekly outfits.

Next Steps

Implement a robust combination algorithm based on color, style, or occasion.
Add category selection for clothing items.
Integrate favorite combinations feature.
Enhance the weekly planner with a calendar view.

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
