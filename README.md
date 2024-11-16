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
* The long-term goal is to reduce the pipeline to incarceration by improving literacy and addressing socio-emotional needs.
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

3.) Generate personalized learning materials based on a review (POST /generate-material).
Recommendation Retrieval:

* Fetch stored recommendations for a student (GET /recommendations/<student_id>).

External APIs:

The backend integrates the ChatGPT API to power intelligent, context-aware recommendations

  
User Stories
* Student
  As a student, I want to log in securely using my account credentials so that I can access personalized recommendations from the AI model.
  After logging in, I can view study materials and feedback specifically tailored to help me improve in my learning journey.
  Teacher

* As a teacher, I want to log in securely to my dashboard to manage my class.
  Once logged in, I can see a list of all the students in my class, access their performance data, and provide feedback to generate AI-powered recommendations for their learning.
  
* Mentor  
  As a mentor, I want to log in to my dashboard to manage my mentees effectively.
  After logging in, I can view all the mentees assigned to me, track their progress, and provide guidance to support their academic and professional growth.
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
* Kayode James-Owolabi
* Wilton Cartwright
