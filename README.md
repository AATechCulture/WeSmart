# WeSmart

<img src="https://github.com/user-attachments/assets/f727cff1-37be-4ee7-9f85-0f7ded146229" alt="Image Description" width="400" height="700" />
<img src="https://github.com/user-attachments/assets/f7d8d039-d2d5-435f-8768-e4366c4526a6" alt="Image Description" width="400" height="700" />

​
## Challenge Statement(s) Addressed 
How can we dismantle the school-to-prison pipeline by addressing inequitable education systems and improving literacy levels in Arkansas through AI-driven solutions?

* Tackling the school-to-prison pipeline in Arkansas.
* Addressing inequitable education systems and improving literacy levels.
* Using AI-driven solutions to promote equitable access and enhance learning outcomes.*

## Project Description 
WeSmart is an AI-driven personalized learning platform aimed at mitigating educational disparities in Arkansas, starting with the Little Rock School District.

How It Works:
* Leverages OpenAI API and educational APIs for adaptive learning.
* Provides gamified and personalized resources to engage K-12 students.
* Features a future mentorship system and social-emotional learning (SEL) modules for holistic student development.

​
## Project Value 
Target Audience:
* Primary: K-12 students, teachers, and mentors in Arkansas.
* Secondary: School administrators and policymakers.

Benefits:
* For Students: Engaging and culturally relevant educational experiences tailored to their needs.
* For Teachers/Mentors: Real-time tracking and actionable insights for personalized intervention.
* The long-term goal is to disrupt the school-to-prison pipeline by enhancing literacy and addressing socio-emotional needs, which has far-reaching impacts across all sectors. For example, improving education reduces crime rates, leading to safer communities; it creates a more skilled and employable workforce, boosting economic growth; and it lowers incarceration rates, reducing the burden on the justice system. Furthermore, addressing socio-emotional challenges fosters healthier individuals who can contribute positively to society, from better family dynamics to increased civic engagement.
​
## Tech Overview 
* Website Deployed Link: https://superb-alfajores-2729f4.netlify.app 
* Frontend: We developed the website using Flutter, ensuring a seamless and responsive user interface. For authentication, we integrated Firebase, providing secure and efficient user management.
  
* Backend: Built with Flask, the backend handles server-side logic, processes data, and serves RESTful APIs. It is hosted on Heroku, ensuring scalability and seamless integration with Firebase Firestore for data storage.
* AI Model Integration: The ChatGPT API analyzes teacher reviews to provide personalized, context-aware recommendations for students, leveraging prompt engineering for accurate and relevant outputs.

## APIS USED

Internal APIs:

1.) Student Management APIs:

* Fetch all students in a class (GET /students).
* Add a new student (POST /students).

2.) Teacher Review and Recommendation APIs:
 
* Submit a teacher’s review (POST /review).

* Generate personalized learning materials based on a review (POST /generate-material).
  
3.) Recommendation Retrieval:
* Fetch stored recommendations for a student (GET /recommendations/<student_id>).

External APIs:

1.) The backend integrates the ChatGPT API to power intelligent, context-aware recommendations

## 💻 Tech Stack:
 ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) ![Heroku](https://img.shields.io/badge/heroku-%23000000.svg?style=for-the-badge&logo=heroku&logoColor=#00C7B7)![Flutter](https://img.shields.io/badge/flutter-%23039BE5.svg?style=for-the-badge&logo=flutter) ![Dart](https://img.shields.io/badge/dart-%23039BE5.svg?style=for-the-badge&logo=dart) ![Flask](https://img.shields.io/badge/flask-%23039BE5.svg?style=for-the-badge&logo=flask)
  
## User Stories
* Student
  As a student, I want to log in securely using my account credentials so that I can access personalized recommendations from the AI model.
  After logging in, I can view study materials and feedback specifically tailored to help me improve in my learning journey.
  Teacher

* As a teacher, I want to log in securely to my dashboard to manage my class.
  Once logged in, I can see a list of all the students in my class, access their performance data, and provide feedback to generate AI-powered recommendations for their learning.
  
* Mentor  
  As a mentor, I want to log in to my dashboard to manage my mentees effectively.
  After logging in, I can view all the mentees assigned to me, track their progress, and provide guidance to support their academic and professional growth.



## Walkthrough: Using Our App
  Welcome to our app! Below is a step-by-step guide to using the app for both Students and Teachers. Follow these steps to explore how tailored recommendations are generated using our AI model and how teachers can manage feedback and create personalized recommendations.

# For Students
* Login as a Student
* Open the app and navigate to the Login screen.
* Use our test student credentials: Email: wisdom@gmail.com, Password: Wisdom
* Click Login. After logging in, you will be able to:
* View tailored recommendations generated specifically for you using our AI model.

# For Teachers
* Signup as a Teacher
* On the Signup screen, select the Teacher role.
* Enter your details (First Name, Last Name, Email, and Password) and click Signup.
* Once registered, you will be provided with a Class Code. This code is unique to your account and will be used by students to link to your class.

# Login as a Teacher
* Navigate to the Login screen and use our test teacher credentials: Email: jons@gmail.com, Password: Gabriella
* Click Login. After logging in, you can:
* View all students in your class.
*Add feedback for students.
* Generate recommendations based on feedback using our AI model.
  
# Connecting Students to a Class
* After signing up as a Teacher, copy your unique Class Code.
* Share the Class Code with your students.
* When students sign up, they will enter the Class Code to link their account to your class.
  
# Creating Recommendations for Students
* Login as a Teacher.
* Navigate to your Class Dashboard to see the list of students linked to your account.
* Select a student from the list.
* Provide feedback in the feedback form.
* Click Generate Recommendations.
* The app will generate personalized recommendations for the selected student based on the feedback and our AI model.
  
# Test the Full Workflow
* To explore how the app works in its entirety:
* Create a new Teacher account.
* Obtain the Class Code after signing up.
* Create a new Student account using the Class Code from the Teacher account.
* Login as a Teacher, provide feedback for the student, and click Generate Recommendations.

​
​
### Link to Video Pitch 
* https://www.loom.com/share/e6228537c2e64ca3b5572a0a4c50eccd?sid=a36f3963-503f-49f9-b9d8-398bf017fc79
​
### Link to Demo Presentation 
https://www.canva.com/design/DAGWme2KBKs/cNWdM29sZbwLmzfWSzY4Tw/edit


​
### Team Checklist ✅
- [x] Team photo
- [x] Team Slack channel
- [x] Communication established with mentor
- [x] Repo creation from this template
- [x] Hangar registration
​
### Project Checklist 
- [x] Presentation complete and linked
- [x] Video pitch recorded and linked
- [x] Code merged to main branch
​
### School Name 
Philander Smith University
​
### Team Name 
PSU Panthers
​
### ✨ Contributors ✨
* Immanuella Umoren
* Otito Udedibor
* Kenna Agbugba
* Adeoluwa James-Owolabi
* Wilton Cartwright
