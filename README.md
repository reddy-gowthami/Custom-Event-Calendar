📅 React Vite Calendar App
This is a simple and interactive Calendar Application built using React and Vite. It allows users to view a monthly calendar, add events with time and description, and edit them. The UI includes icons powered by Boxicons.

🚀 Features
View calendar by month
Navigate to previous/next month
Add event with time and description
Edit existing events
Interactive and responsive UI
Styled using CSS and Boxicons
🛠️ Setup Instructions
Step 1: Create a Vite + React App
npm create vite@latest calendar-app -- --template react
Step-2:
cd calendar-app
npm install
Step 3: Add Boxicons CDN
In index.html, inside the <head> tag, add the following:
<link rel="stylesheet" href="https://unpkg.com/boxicons@latest/css/boxicons.min.css">
Step 4: Run the App
npm run dev


🧑‍💻 Technologies Used:
- React
- Vite
- JavaScript (ES6+)
- CSS
- Boxicons (via CDN)


Notes:
- Events are stored in memory only. They will reset on page refresh.
- Time is entered in 24-hour format.
