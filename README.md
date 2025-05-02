Personal Diary App - Android Mobile Application

My Diary is a personal journaling application that enables users to securely store and manage their daily thoughts, experiences, and reflections.

✅ Key Features
Splash Screen with Progress Bar – Ensures a smooth startup experience.

User Authentication – Secure login and registration using Firebase Authentication.

Email Verification – Enhances security by verifying new accounts.

Diary Notes Management – Users can add, edit, and delete diary entries with an intuitive UI.

Cloud-Based Storage – Firebase Firestore ensures real-time synchronization across devices.

User-Friendly Interface – Simple navigation with an easy-to-use menu for managing entries.

Logout Functionality – Securely log out with just a tap.

🛠️ Tech Stack & Tools Used
Kotlin – For building a robust and scalable Android application.

Android Studio – The IDE for development and testing.

Firebase Authentication – For secure user login and registration.

Firebase Firestore – To store diary entries under a structured collection hierarchy:

scss
Copy
Edit
notes (collection)
  └── UserId (firebaseAuth)
      └── my_notes (collection)
          └── docId (firebaseFirestore)
⚙️ Challenges Faced & Future Improvements
Challenge: Managing Firestore database structures while ensuring real-time synchronization across multiple devices.

Solution: Utilized efficient Firestore collection hierarchies to handle user data securely.

Future Improvements:

Incorporate cloud backups for data redundancy.

Add AI-based mood tracking for enhanced user engagement.
