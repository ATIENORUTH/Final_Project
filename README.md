**AI-Assisted Online Exam Proctoring System**

*A Case Study of Technical University of Mombasa.*

-This project is a web-based platform designed to enhance academic integrity and reduce examination malpractice in remote learning environments. It utilizes Artificial Intelligence and computer vision to provide a scalable solution for maintaining examination standards.


**📋 Table of Contents** 

1_ Project Overview
2_ System Architecture
3_ Features
4_ Technical Stack 
5_ Database Design 
6_ Installation 
7_ Research Context

**🚀 Project Overview**

The system monitors students during exams using real-time video analysis to detect suspicious behaviors such as multiple faces, frequent head movement, and screen switching. It aims to provide an affordable and transparent alternative to proprietary proctoring solutions.

**🏗 System Architecture** 

-The project follows a Three-Tier Architecture:
1. **Front-end**: Interface for students to take exams and for lecturers/admins to manage the system.
2. **Back-end Server**: Manages exam logic, user authentication, and data processing.
3. **AI Module**: Powered by OpenCV for real-time monitoring and face detection.

**✨ Features**

1. *Real-time Monitoring*: Detects candidate presence and identity during the session.
2. *Behavior Detection*: Identifies suspicious movements and environmental anomalies.
3. *Automated Logging*: Records violations with timestamps and evidence (images/video).
4. *Proctoring Reports*: Generates detailed summaries of incidents for institutional review.
5. *Role Management*: Distinct functionalities for Students, Lecturers, and System Administrators.

**🛠 Technical Stack**

1. *Programming Languages*: Python (AI & Logic), JavaScript (Frontend interactions), SQL (Database).
2. *Libraries/Frameworks*: OpenCV (Computer Vision), Web-based UI (HTML/CSS/JS).
3. *Database*: MySQL for structured data storage.
4. *Development Methodology*: Agile, allowing for iterative improvements based on user feedback.


**🗄 Database Design**

The database is normalized to the *Third Normal Form (3NF)* to ensure data integrity.

| Table               | Purpose                                      |
|--------------------|---------------------------------------------|
| Users               | Stores credentials and registration details |
| Exams               | Contains exam titles, schedules, and durations |
| Questions           | Stores MCQ, Essay, and True/False questions |
| Proctoring Logs     | Records specific violations and evidence paths |
| Reports             | Stores summary metrics and remarks for each exam |


**⚙️ Installation** 

1. *Clone the Repository*:Bashgit clone https://github.com/your-username/ai-proctoring-system.git
2. *Database Setup*: Import the provided SQL schema into your MySQL server.
3. *AI Module Config*: Ensure Python and OpenCV are installed.
4. *Hardware Requirements*: A functional webcam and stable lighting are required for accurate detection.

**📖 Research Context**

1. Author: *Brodox George (BSIT/677J/2022)* 
2. Institution: *Technical University of Mombasa* 
3. Supervisor: *Mr. Mwangi* 
4. Date: *January 2026* 
