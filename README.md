
<div align="center">
  <h1 align="center">Face Recognition Attendance System</h1>
  <h1 align="center"><img src="client/public/nulogo.png" alt="NU Logo" width="200" height="200"><br>NIIT University - Capstone Project</h1>
</div>

</p>
</div>



<!-- ABOUT THE PROJECT -->

## About The Project
* This project is made as a part of the Capstone Project for Semester VI of 2020 Batch.
* The project uses the facial recognition technology to mark the attendence of students.
* The project aims to eliminate the current conventional attendance system which is done manually. 
* It detects and matches student face to mark attendance automatically.
* The faculty generates the unique authentication code which is validated on student side to mark attendance.

### Salient Features
* Capturing student image at the time of registration later used to detect face and mark attendance.
* Sending class details email using Nodemailer, editing profile, viewing daily and date-wise attendance sheet as well as the no. of lectures and percentage attendance of each student.
* Sending email automatically to all students absent for the class.
* ChatBox - Feature through which the student and faculty can directly chat with each other implemented using Socket.io
* Dynamic Profile page of Student and faculty showing all their details.


### Built With
* ![Front-end][front-end-shield]
* ![Back-end][back-end-shield]
* ![Database][database-shield]
* ![Tools][tools-shield]


<!-- APP TUTORIAL-->
## Navigating Through The App

## Home Page and About Section

   - Home Page of the website. The project is divided into two modules - Student and Faculty.
   
   <img src="Images/home.png" alt="home page" width="800"/> 
   
   - About Section. The project provides face scanning to mark attendance and is very User friendly.
   
   <img src="Images/about.png" alt="home page" width="800"/>
   
## Student and Faculty Registration

   - Faculty Registration form. The faculty needs to fill in the details and register. The passwords will be validated.
   
   <img src="Images/facultyRegister.png" alt="home page" width="800"/>
   
   - Student Registration form. The student needs to fill the details and capture image which will be stored and used later to mark attendance. The passwords are validated.
   
   <img src="Images/captureImage.png" alt="home page" width="800"/>
   
   
## Student and Faculty Login

   - Faculty Login page. The credentials need to match to login and the authentication is done using JSON Web Token.
   
   <img src="Images/FacultyLogin.png" alt="home page" width="800"/>
   
   - Student Login page. The credentials need to match to login and the authentication is done using JSON Web Token.
   
   <img src="Images/studentLogin.png" alt="home page" width="800"/>
   
## Student and Faculty Profile Page

   - Faculty Profile Page showing all the data dynamically. The faculty can also Edit Profile if he wants. He can generate code, view daily and datewise attendance sheet and also chat with the students.
   
   <img src="Images/facultyProfile.png" alt="home page" width="800"/>
   
   - Student Profile Page showing all the data dynamically along with his image. The Student can also Edit Profile if he wants and enter the authentication code to mark attendance as well as chat with the faculty.
   
   <img src="Images/studentProfile.png" alt="home page" width="800"/>
   
## Generate Code and Send Email

   - The faculty can enter the subject and generate unique authentication code for the student to mark attendance. After generating code a Send Email button appears through which he can automatically share the class details to all the students of the department.
   
   <img src="Images/generateCode.png" alt="home page" width="800"/>
   
   - Email sent to all the students of the department through Nodemailer.
   
   <img src="Images/ClassEmail.png" alt="home page" width="800"/>
   
## Authenticate Code and Mark Attendance

   - The student needs to mark the attendance by entering the subject and the code sent by the faculty.
   
   - The student needs to enter correct code.
   
   <img src="Images/validateCode.png" alt="home page" width="800"/>
   
   - The code will be valid for only 2 minutes and the student has to mark attendance. If a student tries to mark attendance after 2 minutes the attendance will not be marked.
   
   <img src="Images/timeExpired.png" alt="home page" width="800"/>
   
   - If a student enters correct code , a webcam will open will will detect and match student face and automatically mark attendance.
   
   <img src="Images/markingAttendance.png" alt="home page" width="800"/>
   
   <img src="Images/attendanceSuccessfull.png" alt="home page" width="800"/>
   
## View Daily and DateWise Attendance Sheet

   - The faculty can view the daily attendance of all the students of the department.
   
   <img src="Images/dailyAttendance.png" alt="home page" width="800"/>
   
   - He can also automatically send an email to all the students who were absent for the class.
   
   <img src="Images/AbsentEmail.png" alt="home page" width="800"/>
   
   - The faculty can view the date-wise attendance, from-date to to-date by entering the subject. It also shows the no. of lectures attended by each student as well as their percentage attendance.
   
   <img src="Images/monthlyAttendance.png" alt="home page" width="800"/>
   
## ChatBox Feature

   - ChatBox feature implemented using Socket.io

   - The faculty can directly chat with any student of his department. A list of all students of the department appears in the ChatBox. The previous chats are retained using MongoDB.
   
   <img src="Images/FacultyChatbox.png" alt="home page" width="800"/>
   
   - Similarly, the student can also directly chat with any faculty of his department. A list of all faculty members of the department appears in the ChatBox. The previous chats are retained using MongoDB.
   
   <img src="Images/Studentchatbox.png" alt="home page" width="800"/>
   
   - The student and the faculty can now chat with each other with previous chats retained.
   
   <img src="Images/chat.png" alt="home page" width="800"/>


<!--MARKDOWN LINKS-->
[front-end-shield]: https://img.shields.io/badge/Front--end-React%20JS-blueviolet
[back-end-shield]: https://img.shields.io/badge/Back--end-Node%20JS%2C%20Express%2C%20socket.io-blueviolet
[tools-shield]: https://img.shields.io/badge/Tools-JavaScript%20FaceAPI-blueviolet
[database-shield]: https://img.shields.io/badge/Database-MongoDB-blueviolet
