Application Summary: AMAR CADENCE - FitTracker Pro
The code combines a stylized welcome screen with a full-featured fitness tracking application.

1. User Experience Flow:
Welcome Screen (page1.html): The application starts with a full-screen, animated welcome message: "WELCOME TO AMAR CADENCE WEBSITE". It features a starfield background animation and a neon glow effect, fading out after a 6-second delay to set a futuristic, engaging tone.

Main Application (hackathon.html): After the fade-out, the FitTracker Pro Management System appears, preserving the dark, futuristic theme with glass cards, vibrant neon glows, and custom animations.

2. Core Functionality:
The application is a comprehensive Single-Page Application (SPA) with multiple tabbed sections managed by JavaScript:

Tab	Summary of Features
Dashboard	Log new workouts, view weekly progress, and see key stats (Total Workouts, Minutes, Streak). Includes BMI and BMR Calculators.
Analytics	View performance trends, overall workout minutes, and distribution of workout types (Cardio, Strength, etc.).
Planner	Schedule future workouts using a calendar view. Days with activity are visually highlighted.
Goals	Set specific targets (e.g., 5 Workouts/Week, 1000 Calories/Month) and view progress. Tracks multiple achievements (e.g., First Workout, Seven-Day Streak).
Data	Allows the user to export all stored data as a JSON file or reset all application data.

Export to Sheets
3. Technology and Design:
Design: Utilizes Tailwind CSS for a responsive, modern layout, combined with extensive custom CSS for glass morphism and neon glow effects.

Persistence: All workout logs, goals, plans, and achievements are saved directly in the user's browser using localStorage.

Interactivity: The application is highly interactive, using JavaScript to handle form submissions, dynamic content rendering, goal checking, streak calculation, and motivational pop-up notifications.
