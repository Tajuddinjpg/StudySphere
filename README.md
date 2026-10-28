# StudySphere Android Application

A short Android Studio assignment project built with Java and XML.

## Features
- Splash screen
- Login with basic validation
- Register with name, email, password and confirmation
- Forgot password and simulated reset flow
- Dashboard with module cards
- Profile information and logout
- Explicit Intents between Activities
- Default strings and night-mode colors
- LinearLayout, GridLayout, and ConstraintLayout examples

## Open and run
1. Extract `StudySphereAndroid.zip`.
2. Open Android Studio.
3. Choose **Open** and select the extracted `StudySphereAndroid` folder (the folder containing `settings.gradle`).
4. Allow Gradle sync to finish. Use JDK 17 if Android Studio asks.
5. If prompted to install Android SDK Platform 35, accept it.
6. Select an emulator or connect an Android phone, then press **Run**.

## Demo login
- Email: `student@example.com`
- Password: `123456`

Any valid email with a password of at least 6 characters also passes the demo login validation. This is a front-end coursework demo only; it does not use a real server or save user accounts securely.

## Notes
- Forgot Password and Reset Password simulate a recovery flow locally.
- For a production app, use a secure backend and never store passwords in plain text.
