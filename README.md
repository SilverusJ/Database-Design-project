# Database-Design-project


## Objective


The objective of this database project is to develop a centralized, secure, and efficient system that enhances the management of critical healthcare operations, including patient records, staff information, appointments, laboratory results, and billing. The system aims to improve data accessibility, streamline workflows, enforce role-based access controls, and ensure data accuracy and integrity, ultimately contributing to better operational efficiency and patient care quality within the healthcare institution.

### Skills Learned


- Database Design and Modeling: Creating ER diagrams and relational database schemas for complex systems.  
- SQL Proficiency: Writing queries for table creation, data insertion, and database management.  
- Access Control Implementation: Setting up role-based privileges for secure data access.  
- Data Security Practices: Applying techniques to prevent SQL injection and ensure secure data handling.  
- Relational Database Management: Maintaining data accuracy and integrity with primary and foreign key constraints.  
- Testing and Debugging: Populating databases with test data and resolving implementation issues.  
- Documentation and Reporting: Recording objectives, design processes, and outcomes effectively.  


### Tools Used


- SQL Workbench
- SQL Shell

## Detailed ER Diagram and Relational Database Schema

2.1 ER Diagram

The ER diagram showcases relationships between the following entities: Patients, Doctors, Nurses, Appointments, Lab Results, and Bills
 ![IMG_8466 (1)](https://github.com/user-attachments/assets/a2885138-a6df-4dcc-aa61-5dd644e82a0c)





2.2 Relational Database Schema

![IMG_8465](https://github.com/user-attachments/assets/e33a34a7-0d47-44b1-b875-2b8707253d70)

## Database Implementation
3.1 Description of the Database Implementation
The implementation involved creating six relational tables with appropriate primary and foreign key constraints. Fake data was added for testing.

 3.2 Screenshots of Database Creation

1. Table Creation Commands 
 ![Screenshot 2024-12-02 221222](https://github.com/user-attachments/assets/240960ec-eff9-4963-9d1f-1b10f6736b0e)



2. Data Insertion Commands
 ![Screenshot 2024-12-02 221245](https://github.com/user-attachments/assets/90e9a1ac-58f4-4fbb-aa31-4d7e4a8a9d60)

## Access Control Implementation
4.1 Overview of Access Control
Roles were defined as admin, doctor, nurse, receptionist, and billing. Each role was assigned privileges tailored to their responsibilities.

4.2 Implementation Commands
Examples of user creation and privilege assignment:
 ![Screenshot 2024-12-02 221322](https://github.com/user-attachments/assets/a0428178-2d25-4bfc-9624-8c15df2f4db4)

 ![Screenshot 2024-12-03 141327](https://github.com/user-attachments/assets/ce0aea67-5c0c-43e1-af23-778387cad43a)
  

4.3 Privilege assignment implementation
This shows examples of some of the users and with tables they have privileges for;

Nurses

![Screenshot 2024-12-09 003835](https://github.com/user-attachments/assets/0692bfe7-0a68-43e7-bd39-c8048683d161)

 
Receptionist

![Screenshot 2024-12-08 231816](https://github.com/user-attachments/assets/96553545-96e8-4774-9107-8ff804d8da36)

   
 
Billing

![Screenshot 2024-12-02 234200](https://github.com/user-attachments/assets/e1fd8497-2f28-445d-b50e-eb76c7a76a9f)

 
 

## Protecting Against SQL Injection Attacks
5.1 Overview
SQL injection is a common attack that manipulates queries to gain unauthorized access to data.

5.2 Mitigation Techniques

To prevent SQL injection:
•	Use prepared statements: Prevents malicious inputs by separating SQL logic from data.
•	Validate input data: Ensures inputs conform to expected formats.
•	Restrict user privileges: Limits access to essential functions only.

5.3 Prepared Statements Example 

 ![Screenshot 2024-12-03 155451](https://github.com/user-attachments/assets/8aeb61cf-3b36-4545-9f3b-077131f2ec18)




