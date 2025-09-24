📌 Quizoo – Secure Online Quiz Platform

Quizoo is a free and secure platform for conducting online quizzes with advanced anti-cheating features. Built with Django, Nginx, Redis, and Docker, it ensures smooth exam management and a reliable test-taking experience.

🔑 Key Features

LockDown Browser – Restricts console access, switching apps, screenshots, and external sites.

Dynamic Question Sequencing – Randomizes order & disables back navigation to prevent cheating.

Automated Image Proctoring (in progress) – Uses webcam monitoring & analytics to detect suspicious behavior.

Personalized Test Reports – Generates detailed reports with timestamps, question-wise activity, and screenshots.

Easy Result Sharing – Export to Excel or auto-send results via email.

🏗 Tech Stack & Deployment

Backend: Django with SQLite (moving to PostgreSQL)

Frontend: Django templates + static hosting via NGINX

Server: uWSGI + Docker for scalable deployment

Cache/Session: Redis for backend session management

🚀 Future Enhancements

Full AI-powered image/audio proctoring

Live announcements during exams

Admin-controlled live screen monitoring

Category-wise question selection

