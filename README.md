🎉 FunQ – Friends Life Quiz
FunQ is a light-hearted, interactive personality quiz web app where users answer fun questions related to their love life, friendships, and habits — and get a custom result title based on their answers!
Perfectly designed for mobile and desktop users, this app combines a modern UI with backend scoring logic in Java.

✨ Features
🎨 Stylish and responsive UI with emojis, gradients, and animations

✍️ User-friendly quiz form built with Thymeleaf

🧠 Scoring system calculates results from radio button choices

📝 Custom titles based on total score

🗃️ Data storage using Spring Data JPA & MySQL

📆 Auto timestamping for quiz submissions

🛠 Tech Stack
Layer	Technology Used
Backend	Java, Spring Boot, Spring MVC, Spring Data JPA
Frontend	HTML, CSS, Thymeleaf (with help from ChatGPT for UI styling)
Database	MySQL
Tools	IntelliJ / VS Code, Git, GitHub
Design	Mobile-first responsive layout, gradient backgrounds, emoji-rich UI



🚀 How It Works
✅ User visits the Welcome page

🧩 Starts the Quiz

📤 Form is submitted and processed in the backend

🔢 Scores are calculated based on selected answers

🏆 User sees their result title and total score

🔁 Option to replay the quiz

🧩 Project Structure
css
Copy
Edit
src/
 ├── main/
 │   ├── java/
 │   │   └── com.example.friendsgame/
 │   │       ├── controller/      → Handles routes like /form, /submit
 │   │       ├── entity/          → QuizResponse.java (model)
 │   │       ├── repository/      → Spring Data JPA for MySQL
 │   │       └── service/         → Custom scoring logic
 │   └── resources/
 │       ├── templates/
 │       │   ├── welcome.html     → Welcome screen
 │       │   ├── form.html        → form form
 │       │   └── result.html      → Result display
 │       └── application.properties
✅ Roles and Responsibilities
🧪 Designed & implemented quiz logic using Java and Spring Boot

🎨 Created stylish frontend using HTML, CSS, Thymeleaf, and ChatGPT AI support

💾 Integrated MySQL database with Spring Data JPA for storing quiz data

🧠 Developed custom scoring service to calculate results

📱 Ensured full mobile compatibility with animations and responsive design

🎯 What I Learned
Real-world Spring Boot MVC application structure

Form handling and binding using Thymeleaf

Backend-to-database integration using JPA

Frontend enhancement using gradient backgrounds and responsive design

Version control using Git and GitHub

💡 Future Improvements
🔗 Social sharing of results

🧍 Leaderboard feature

📲 Deployment on cloud platform (e.g., Render, Vercel, or Heroku)

🎨 More quiz categories (e.g., Friendship, Food, Travel etc.)


🙋‍♀️ About Me
I'm a passionate Java developer fresher with a strong interest in backend development and building interactive apps.
This project reflects my ability to combine logic and creativity in a full-stack environment.

