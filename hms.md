# Modules and Features

## Users
1. Admin
2. Doctor
3. Accountant
4. Laboratorist
5. Nurse, Pharmacist
6. Receptionist
7. Representative
8. Case Manager
9. Patient.

## Modules
1. Department
2. Doctor
3. Patient
4. Schedule
5. Appointment
6. Account Manager
7. Prescription
8. Insurance
9. Hospital Activities
10. Bed Manager
11. Human Resources
12. Billing
13. SMS
14. Messages
15. Noticeboard
16. Enquiry
17. Mail
18. Case Manager
19. Setting

### Modules, Features and user role

1. Department:
- Add Department System `admin`
- Department List System `admin`

2. Doctor
- Add Doctor `admin`
- Doctor List `admin` `doctor`

3. Patient
- Add Patient `admin` `doctor`
- Patient List & Info `admin` `doctor` `accountant`
- Add Document `admin` `doctor`
- Document List `admin` `doctor`

4. Schedule
- Add Schedule `admin` `doctor`
- Schedule List `admin` `doctor`

5. Appointment
Add Appointment `admin` `doctor`
Appointment List `admin` `doctor`
Assign by All `admin`
Assign by Doctor `admin` `doctor`
Assign by Representative `admin`
Assign to Doctor `admin` `doctor`

6. Account Manager
Add Account `admin` `accountant`
Account List `admin` `accountant`
Add Invoice `admin` `accountant`
Invoice List `admin` `accountant`
Add Payment System `admin` `accountant`
Payment List `admin` `accountant`
Report `admin` `accountant`
Debit Report `admin` `accountant`
Credit Report `admin` `accountant`

6. Prescription
Add Patient Case Study `admin` `doctor`
Patient Case Study List `admin` `doctor`
Add Prescription `doctor`
Prescription List `admin` `doctor`

7. Insurance
Add Insurance `admin`
Insurance List `admin`
Add Limit Approval `admin`
Limit Approval List `admin`

8. Hospital Activities 
Add Birth Report `admin` `doctor`
Birth Report `admin` `doctor`
Add Death Report `admin` `doctor`
Death Report `admin` `doctor`
Add Operation Report `admin` `doctor` 
Operation Report `admin` `doctor`
Add Investigation Report `admin` `laboratorist`
Investigation Report `admin` `doctor` `laboratorist`
Add Medicine Category `admin`
Medicine Category List `admin`
Add Medicine `admin`
Medicine List `admin`

9. Bed Manager
Add Bed `admin`
Bed List `admin` `nurse`
Bed Assign `admin` `doctor`
Bed Assign List `admin` `nurse`
Report `admin` `doctor` `nurse`

1.  Human Resources
Add Employee `admin`
Accountant List `admin`
Laboratories List `admin` `laboratorist`
Nures List `admin` 
Pharmacist List `admin`
Receptionist List `admin`
Representative List `admin`
Case Manager List `admin`

11. Billing
Add Service `admin`
Service List `admin`
Add Package `admin`
Package List `admin`
Add Patient Admission `admin`
Patient Admission List `admin`
Add Advance Payment `admin`
Advance Payment List `admin`
Add Bill `admin`
Bill List `admin`

12. Enquiry

13. SMS `admin`
Gateway Setting `admin`
SMS Template `admin`
SMS Schedule `admin`
Send Custom SMS `admin` 
Custom SMS List `admin` 
Auto SMS Report `admin`
New SMS `admin` `doctor` `laboratorist` `nurse`
User SMS List `admin` `doctor` `laboratorist` `nurse`

1.  Messages
New Message `admin` `doctor` `accountant` `laboratorist` `nurse`
Inbox `admin` `doctor` `accountant` `laboratorist` `nurse`
Sent `admin` `doctor` `accountant` `laboratorist` `nurse`

15. Noticeboard
Add Notice `admin`
Notice List `admin` `doctor` `accountant` `laboratorist` `nurse`

16. Mail
Send Mail `admin` `doctor` `accountant` `laboratorist` `nurse`
Mail Setting `admin`

17. Case Manager
Add Patient `admin`
Patient List `admin` `doctor` 

18. Setting
App Setting `admin`
Language Setting `admin`

