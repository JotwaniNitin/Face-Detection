# Face-Detection

### Introduction
The Face Detection project will be a boon in classrooms by saving time in rollcalls to straigtaway jumping to lectures and learning. It is a method to speed up the commencement of tutorials in class and is a leap into digitalisation of classrooms.

### FaceRek Attendance
The website -- FaceRek Attendance acts an interactive web app for the teachers and students. At the present moment the website has the minimal functonalities of the home, about, login/register page with a dashboard for students. 
<br>

<h3>Technicalties</h3>
The dashboard uses the <bold> AWS Rekognition API </bold> for training and test for facial recognition. It also uses <bold> AWS Polly </bold> for audio features. The dashboard is presently only for collecting and checking the facial pictures. 
<br>
Recognition uses ruby and bundle to run the API.
<br>
In a separate folder named FaceRecogniion Python, the facial recognition is coded and can be used on terminal. It uses keras library and can be integrated with MongoDB for database management. Though, I did not find a way to integrate this too a web application, I have moved forward with Rekognition. 
<br>
Another option, was the Face API by Microsoft Azure services. On exploring this, I found AWS is a lighter and more user friendly API to be integrated. The AWS has been integrated with the HTML using the JPEG Camera library on GitHub by amw. This could not be done with MSF. 
<br>
<br>
As far as the <bold>added functionalities</bold> are concerned, on signing in the website will be built with the following features. 
1. A separate dashboard for teachers and students. 
  i. The teachers can view all classes, 
  ii. check attendance,
  iii. schedule classes,
  iv. enable attendance,
  v. view leave applications.
  
  a. The students can view all classes,
  b. check their attendance,
  c. give attendance,
  d. submit leave applications
  
2. Class IDs will be generated by teachers.
3. Database will be linked to website using MySQL.
   
