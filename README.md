I have built a valuable attendance and login service for both teachers and students. It reduces manual process errors by this automated and reliable login system which marks the attendance of students and redirects them to the online classroom using facial recognition technology.


Install a module

Download or clone the repository
Download the module from https://drive.google.com/file/d/1RxvBRRExA2fiIfZow6MpqfoRDtIs4C6Y/view?usp=sharing and move this file to the backend folder.
Import the project to your favourit IDE


Set up the frontend

Open a terminal and enter the frontend folder:
cd frontend

Install the packages:
npm install

Start the frontend:
ng serve


Set up the backend

Open another terminal to create and activate a virtual enviroment:
python3 -m venv env
source env/bin/activate

Enter the backend folder:
cd backend

Install the requirements:
pip install -r requirement.txt

Start the app:
python attendence_app.py   

Follow the local path in the first terminal to use the web app.


Tech Used 💻

Build With -
Python 3.10

Module Used -
All The Module are Latest Version.
OpenCV
Pillow
Numpy
Flask
PyTorch

Face Recognition Algorithms -
MTCNN
ResNet50

Software Used -
VS CODE
Git

Database -
SQL lite

Frontend -
HTML
CSS
Angular
Bootstrap


Usage guide/ Application flow 

Test teacher username: teacher
Test teacher password: 123

Landing Page:
Continue Signing Up/In by clicking the highlighted buttons.
All links except those of Sign In and Sign Up lead to the original Microsoft Teams website (these have been added just for information purposes, no copyright infringement is intended).

Teacher Signup & Registering Students:
Use the username, password provided by the admin to signup
Enter student details, class link and student's picture and submit. Similarly register all the students

Student Login:
Head to the student's login page
Enter the required details and give access to the camera
Click a clear image and validate it to receive the class link and past attendance records

Teacher's attendance records:
Login to the teacher's portal and select check attendance records
The teacher can view attendance records for any particular roll number
