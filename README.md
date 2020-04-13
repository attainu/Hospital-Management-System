<img src="public/images/logo.png" width="100%"><br>
Hospital Plus - Hospital Management System<br>
-----------------------------------------------<br>
DESIGNED & CREATED BY: RAHUL ABHISHEK<br>
PRESENTED TO: ATTAINU<br>
INSTRUCTOR: SUNDEEP SIR<br>
GUIDED BY: ABDULLAH (MENTOR)<br>

About Hospital Plus:<br>
◦ Hospital Plus is a web application for managing hospitals rooms and determining the patient's priority for
isolation. The app provides a centralized hub for managing the patients and planning their distribution
across hospital’s rooms.<br>
◦ It allows nurses/hospital staff to keep track of the patients and their diseases in real time and to have an
overview over the patients and rooms, and better manage the rooms assignment across patients.<br>
◦ Also it has feature like patients score of their disease that helps management to keep in priority to that
patient who is really need for immediate treatment.<br>

<img src="public/images/hsopital.jpg" width="100%"><br>
<a href="Hospital-Plus-AttainU/Hospital-Plus_Hospital-Management-System.pdf">PDF Documents</a>

How To Install:
----------------------------------------------------------------------------------------------------------------
Live Web App: <a href="https://hospital-plus-2020.herokuapp.com/" target="_blank">https://hospital-plus-2020.herokuapp.com/</a> ( Username: attainu | Password: rahul123 )

1. Download the repository: git clone https://github.com/AttainU/Hospital-Management-System
2. Open the Terminal (Linux & MacOS) or PowerShell (Windows) and change directory to the project folder.
3. Type ‘npm install’ in the Terminal (PowerShell) and press Enter. All the dependencies would be installed.
4. Go back to the Terminal (PowerShell) and be sure that you are pointing inside the project folder. To open the application, type ‘node app.js’ and press Enter.
5. The application should be live on the local port 3000.
6. Type http://localhost:3000/ into a browser.
7. To login use the username: attainu and the password: rahul123
8. Now you should be inside the application.
------------------------------------------------------------------------------------------------------------------

How To Use:
------------------------------------------------------------------------------------------------------------------
◦ Dashboard:
-----------------------------------------------
◦ Data about patients and rooms is available here. The page is split into three tables.<br>
◦ Double click on patient for update their disease or delete that patient.<br>
◦ To Assign room, first click on available room then click on patient, now popup will appear, you need to confirm that.<br>
◦ To clear the red warning sign you need to go on the patient’s personal page. To do that, you have to double click on his name. By clicking on the ‘Update button’ on the bottom of the page, the patient’s diagnosis in updated for the next 1 hours (consequently, the red warning sign disappears).<br>


◦ Add Patient Page:
-----------------------------------------------
◦ You can add a new patient in the system with his personal details and his diseases. The application
automatically computes the score of the patient based on the entered diseases.

◦ System setting:
-----------------------------------------------
◦ The control center of the application. It allows users to manage the diseases & rooms of the Hospital and
create new accounts.