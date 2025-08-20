🤖 Attendance Guardian: AI WhatsApp Chatbot
📌 The Problem Statement
Many students struggle to keep track of their attendance, leading to an unexpected drop below the mandatory 75% threshold. This can result in ineligibility to sit for final exams and academic penalties. Manually calculating attendance and leave eligibility is tedious and prone to error.

🚀 How the Prototype Solves the Problem
Our Attendance Guardian prototype is a helpful AI-powered chatbot seamlessly integrated with WhatsApp. It provides an immediate and accurate way for students to manage their attendance. The chatbot solves the problem by:

Proactively monitoring attendance: Students can simply send a message to the bot to get a real-time update on their attendance percentage.

Calculating leave eligibility: The bot instantly calculates the exact number of classes a student can miss while maintaining the 75% attendance rule.

Sending timely warnings: It automatically sends a warning message to the student when their attendance drops below the critical 75% mark, prompting them to take corrective action before it's too late.

This shifts the burden from the student to an automated system, ensuring they stay informed and on track with their academic requirements.

💻 Technologies & Tools Used
Frontend: The chatbot interface and user interactions are powered by React.js, providing a responsive and modern web-based experience.

Backend: A server-side language (e.g., Node.js with Express) is used to handle API calls, process attendance data, and communicate with the WhatsApp API.

AI/LLM: The core logic is powered by a Large Language Model (LLM) like Gemini, which processes natural language queries to provide accurate attendance calculations and responses.

Messaging API: The WhatsApp Business API is used to enable seamless communication between the user and the chatbot.

📊 Current Progress Status
This prototype is a proof of concept with the core functionalities for attendance calculation and leave management already implemented.

Completed:

AI logic for calculating remaining leaves.

Basic integration with a messaging platform.

Functionality to send an automated warning message.

Pending Work:

Integration with a school/university attendance database for real-time data sync.

Development of a user-friendly web interface for initial setup and tracking.

User authentication and security features.

📸 Screenshots of the Prototype
User's Query	Leave Calculation	Low Attendance Warning
A screenshot of the user's query asking "How many leaves can I take?"	A screenshot of the chatbot's response showing the exact number of classes they can miss.	A screenshot of a warning message from the bot when attendance falls below 75%.
