




# Anti-Cheat Exam App  🌟

<p align="center">  
<img src="https://user-images.githubusercontent.com/28570857/178106216-25d91b1c-06cf-42fa-85fc-cf3540868b1f.png"/>  
</p>



## Features and Interfaces

1. Login Page
   - Login with the provided user id and password
   - Powered by JWT tokens

2. Home page
   - Shows all the exams assigned to the user
   - The user can start an exam only on the correct timeslot
   - Logout through button in the app bar

3. Exam Page
   - The user can answer MCQ-based questions
   - The user can also view their progress

   - ![image](https://user-images.githubusercontent.com/28570857/179022654-f59b6b0c-77d7-48f4-9a55-32813378a696.png)


7. AI-powered face motion detector
   - We've used Google's on-device `ml-kit` to track the motion of the user's face.
   - We can check if a user is trying to cheat by monitoring the position of their face

   - ![image](https://user-images.githubusercontent.com/28570857/179022316-45cf8a11-9d5a-411f-b4ce-89d1ea02e478.png)



## Tech stack

#### Frontend
- Flutter
- MobX + Provider

#### Backend
- Nodejs
- Express
- MongoDB

#### Frontend

- Next.js (React)
- TypeScript
- Redux


#### Other Tools
- Google's on-device ML Kit


## Instructions


1. Import the project through Android Studio or clone it
   - `https://github.com/prathamesh-mutkure/anti-cheat-exam-app.git`
3. Install flutter packages
   - `flutter pub get`
4. Generate store classes
   - `flutter packages pub run build_runner build`
5. Create a `.env` file and set the following variables
   -  `BACKEND_URL`
6. Connect your device or emulator and run the app
   - `flutter run`
7. The app is now running

