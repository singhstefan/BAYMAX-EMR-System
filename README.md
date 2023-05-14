# BAYMAX-EMR-System

HOME PAGE
-First screen the user sees when opening the page
-Provides a welcome quote with breif description about the website
-User has option to log in with existing account or register as a new user

registration.html
-Accessed when a user wants to create a new account
-Requires email, username, and password
-Has an option to take the user to a login page if they ever need to switch

demographics1.html
-After the user enters his information into the registration section, they are prompted to enter some of their personal information 
-This information gets stored into the database for the user to see later, along with other doctors

demographics2.html
-The demographics page is split into two sections to make it more readable and user friendly
-The user further inputs their personal information to be stored into the database for doctors to see

login.html
-If the user already has an account they are taken to the login page from the homescreen
-Email and password are required for login
-Can also redirect to registration page and forgot password page

forgotPassword.php
-User comes here to reset their password. Prompted with email, username, and new password input boxes
-They can then login or be taken to the registration page

DoctorPatientListView.php
-Initial screen the doctor sees after logging in
-Contains the list of all patients in the system, along with vitals from their most recent report
-Also has a view button that brings up a more detailed view of a patient 

johndoe.html
-This is an example of what the doctor would see after clicking into a specific patient from the patient list
-Allows the doctor to see a more detailed look at the patient. Includes information about the patients demographics, allergies, and medications the patient is currently on
-Has a section for medical report that shows what the patient has been through along with view and print buttons that allow a more detailed view of the report or an option to print the report

doctorpatientreports.html
-Allows the doctor to see the patients that they are assigned to
-Has functionalities to view the patient (similar to the one in patientlist), view the patients last encounter with them, or print out the report

drviewreportjd.html
-This screen is reached by clicking on the view button in "View Encounter" on the reports page
-Allows the doctor to easily see all of the patients previous conditions
-Doctor can view these conditions 

UPDATED_backpain.html
-If the doctor wants to view the condition of a patient they can click on this page, along with any other UPDATED html page for the given condition
-Shows a table of all the pateints previous reports including the date it happened, the symptoms experienced, the diagnosis, treatment, and the followup

exampleInitialDoctorViewcal.html
-This is reached after clicking the view appointments button for a doctor
-Allows doctor to create events for a patient, requiring them to enter a date and time to create an appointment for a patient
-Doctor can also use the calendar displayed to manage his week and see what patient appointments they have upcoming, or patient appointments that previously have passed

FINISHED_patientMedicalRecords.php
-Initial view for a patient after they log in
-Shows a table of all the personal information they provided including demographics, allergies, medications, and a medical report section 
-Medical report section shows their previous conditions along with a view button to view the report, and a print button incase they want to print a copy for themselves

PatientDoctorReports.php
-Patients version of seeing their previous visits
-Shows the visit date, the doctor they met with, and has a section for their vitals 
-Patient has the option to view their report which was created by a doctor

dislocated_shoulder_report.html
-This page comes up when a patient hits view 
-Shows a detailed report of their last visit 
-Report created by a doctor

patientCalendar.php
-Patient can see all of their upcoming and previous appointments
-Can scroll through calendar and see appointments far into the future

anxiety.html
-This page comes from a doctors "reports" tab under "view encounter"
-When the doctor clicks on a part of the patients body, they are able to see a detailed report 



































