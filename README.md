# HabitTracker

Our web application empowers users to efficiently manage their daily habits, enabling them to effortlessly create, update, and delete habits while effectively tracking their progress. 
This user-specific platform allows individuals to monitor their habits, marking them as 'completed' or 'incomplete' based on their daily activities. 
Our project is built upon a robust tech stack, incorporating Node.js for server-side scripting, Express for streamlined HTTP request handling and routing, 
MongoDB for secure data storage and management, and EJS for seamless rendering of views and templates

## Installation
To run this application on your local machine, please follow these steps:

$ npm install 
```
Start the application using the following command:
```
$ npm start 
```
Open the application in your web browser by visiting the following URL:
```
$ http://localhost:8000 
```

Once you have the application up and running, you can begin using it by following these steps:

1. Sign Up/Sign In: Log in to your account or create a new one if you haven't already.

2. Add a New Habit: Click on the "Add Habit" button to create a fresh habit.

3. Habit Name: Enter the name of the habit you wish to track.

4.Save Your Habit: Click on the "Save" button to store the habit in your profile.

5.Track Progress: To mark a habit as complete or incomplete for the day, simply click on the corresponding icon.

6.Delete a Habit: If you want to remove a habit, click on the "Delete" icon next to it.

7.View Today's Habits: To see the habits scheduled for today, click on the "Show Daily" button.

8.Edit a Habit: If you need to make changes to a habit, click on the "Edit" icon next to it.

## Folder Structure
```
Habit Tracker
    |
    |               |--->css
    |--->assets---->|--->img
    |               |---> js
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport_local.js
    |
    |                  |-->habit_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->user_controller.js
    |
    |               |-->habit.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->habit.js
    |--->routes---->|-->index.js
    |               |-->user.js
    |
    |              
    |              |--->_header.ejs
    |              |--->404.ejs
    |              |--->daily_view.ejs
    |              |--->forget_password.ejs
    |--->views---->|--->home.ejs
    |              |--->layout.ejs
    |              |--->user_sign_in.ejs
    |              |--->user_sign_up.ejs
    |              |--->weekly_view.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    ...


