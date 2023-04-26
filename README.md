# FaciHubSMS
## FaciHub Student Management System

A web-based enrollment, grading, record-management and forms & reports generation system made exclusively for Headwaters College - Elizabeth Campus Inc. to help manage thousands of students across semesters and academic years.

Source codes are intentionally hidden. Contact the institution for verification.

## Login Screen
- All employee accounts are created by the System Administrators (which is an IT account).
- There are three types of user (and views) namely: IT, Admin, and Faculty.
![Login](https://github.com/MarOmay/FaciHubSMS/blob/main/login.png)

## Faculty Views
- Instructors are able to generate list of their assigned classes per class section and subject.
- They are also able to print Attendance Sheet templates pre-supplied with students' names.
- If IT settings allow, they will be able to post grades during midterm and finals. The final grade is automatically computed based on the prescribed formula.
![MyClasses](https://github.com/MarOmay/FaciHubSMS/blob/main/faculty_myClasses.png)
![Grading](https://github.com/MarOmay/FaciHubSMS/blob/main/faculty_grading.png)

## Admin Views - Enrollment
- Following the client's requirement, only the users with Admin account can enroll a student through the system.
- Selecting a section automatically displays the subject attached to the section's track. Subjects can be unchecked so the student won't be enrolled to that specific subject (e.g irregular students).
- Once the student information is submitted, validated by the system and finalized, the generated Certificate of Enrollment (COE) will automatically be prepared for printing or download. If needed, it can be reprinted later.
![Enrollment](https://github.com/MarOmay/FaciHubSMS/blob/main/admin_enrollment.png)
![COE](https://github.com/MarOmay/FaciHubSMS/blob/main/admin_coe.png)

## Admin Views - Registrations
- This page displays the records of all enrolled students.
- The search feature makes it easier to find a specific registration when managing thousands of students.
- This is also where COE's can be reprinted when needed.
![Enrollment](https://github.com/MarOmay/FaciHubSMS/blob/main/admin_registrations.png)
![COE](https://github.com/MarOmay/FaciHubSMS/blob/main/admin_reprintCoe.png)

## Admin Views - Forms & Reports
- This page is where all records can be generated in the form of COE, Report of Grades, or relevant summaries.
![Reports](https://github.com/MarOmay/FaciHubSMS/blob/main/admin_reports.png)

## IT Views - User Management
- Only users using an IT account can create, edit information of, reset password of and delete an employee account.
![UserMngt](https://github.com/MarOmay/FaciHubSMS/blob/main/it_manageUsers.png)

## IT Views - Academic Year & Other Info
- The current Academic Year and Semester can be set here which play a crucial role in maintaining the records and making sure that the reports are generated with correct information.
- The form validator, whose name will be printed as the signatory in various forms, can be modified here without affecting other records.
- Posting of Grades and Modification of vital configurations can also be done in this page.
![Cycle](https://github.com/MarOmay/FaciHubSMS/blob/main/it_cycleSettings.png)

## IT Views - Managing Subjects & Tracks
- Subjects can be added and edited in this page. The CODE is used internally by the system, while the ALIAS is the "SUBJECT CODE" that will be reflected in generated forms and reports.
- Tracks can also be added and manage by an IT account user. They can attach subjects to tracks which will be relevant during the enrollment process.
![MngSub](https://github.com/MarOmay/FaciHubSMS/blob/main/it_manageSubjects.png)
![Mngtrack](https://github.com/MarOmay/FaciHubSMS/blob/main/it_managetracks.png)

## IT Views - Managing Sections & Assigning Instructors
- This allows for adding of academic subjects and modifying subject information.
- Each section can be assigned a set of intructors for each subject they have.
![MngSec](https://github.com/MarOmay/FaciHubSMS/blob/main/it_manageSections.png)
![AssignInst](https://github.com/MarOmay/FaciHubSMS/blob/main/it_assignInst.png)

Created by Mar Alexis O. Omay
