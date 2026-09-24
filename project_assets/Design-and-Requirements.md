# BJJ Fitness App — Design & Requirements

## Design

The BJJ Fitness App will be developed as a mobile application using
Flutter and Dart.

Firebase services will provide the backend functionality needed by
the application.

### Planned Architecture

- Flutter / Dart will provide the mobile user interface.
- Firebase Authentication will manage account registration, login,
  logout, and password reset.
- Cloud Firestore will store application data including user profiles,
  training sessions, nutrition information, recovery information,
  and technique data.
- Firebase Storage will store user-uploaded files such as profile pictures.


Basic application flow:

User → Flutter Mobile App → Firebase Services

Firebase Authentication → User Authentication

Cloud Firestore → Application Data

Firebase Storage → Images / Files


## Requirements

### User Accounts & Profile

Users must be able to:

- Register an account
- Log in and log out
- Reset a forgotten password
- Create a user profile
- Upload a profile picture
- Select their current BJJ belt
- Enter their age or age range
- Set a weekly training goal
- Set fitness and nutrition goals
- Edit their profile


### Training Log

Users must be able to:

- Log a training session
- Record the date and time of a session
- Record session duration
- Add notes
- Record techniques practiced
- Record sparring information
- View previous training sessions
- Edit previous sessions
- Delete previous sessions


### Technique Library

Users must be able to:

- Browse BJJ techniques
- Browse techniques by category, such as:
  - Takedowns
  - Submissions
  - Sweeps
  - Escapes
  - Guard techniques
- View a description of a technique
- View its difficulty level
- Access instructional videos


### Progress Tracking

The application should provide a weekly training summary containing:

- Number of training sessions
- Total hours trained
- Number of sparring rounds
- Techniques practiced
- Progress toward the user's weekly training goal


### Nutrition

Users must be able to:

- Record their current weight
- Set a goal weight
- Enter height
- Select an activity level
- View calorie targets
- View protein, carbohydrate, and fat targets
- Log food


### Recovery

Users will be able to record recovery-related information to help
monitor their training and fitness progress.

Specific recovery features will be refined during later development.
