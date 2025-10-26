# MIST 4610 GROUP 8 Project-1

## Team Name:
CRN:39217 Group 8

## Team Members:
1. Vishal Ramajayam (@vishalramajayam-art)
2. Bhavya Siva (@bhavyasiva)
3. Sheshasri Mallibhatti (@sheshasrimallibhatti-dot)
4. Huzaifah Malik (@githubhandle)

---

## Problem Description
The objective of this project is to create and set up a relational database for the everyday operations of a tutoring and learning center.  The Student is the central entity in this model. They are enrolled in different academic subjects and given a tutoring plan.  The tutoring center sets up a lot of lessons in classrooms with tutors who are also experts in certain subjects.  The system keeps track of students, their parents or guardians, tutors, subjects, tutoring plans, scheduled sessions, classroom locations, and academic progress through tests and reports.  It also keeps track of payments and assessments to show both academic and financial activity.  We hope that this database will help the tutoring center make decisions and run more smoothly.

---

## Data Model
Explanation of Data Model:
This database is meant to help run a tutoring center by keeping track of students, their parents, tutors, subjects, tutoring plans, scheduled sessions, payments, and grades. The student entity is the most important part of the model. It is linked to a parent or guardian who is in charge of enrollment and payment. Also, each student is in a specific plan that sets the costs and the number of tutoring sessions they can have. Tutors teach sessions in a classroom and link them to a subject. A bridge entity connects students to the sessions they attend, which keeps track of attendance. The model also keeps track of students' academic progress by connecting them to tests and progress reports that show how they are doing over time. Additionally, payment records capture financial transactions made by guardians on behalf of the student. The model does not keep track of things like tutor pay, detailed curriculum content, real-time scheduling conflicts, messaging/communication logs, or external school data that isn't related to tutoring operations. Overall, this design helps a tutoring center with both academic and administrative tasks. It lets you see how many students are participating, how much work the tutors have, how much demand there is for each subject, and financial performance of the center. 


<img width="1181" height="1049" alt="MIST 4610 Project 1 Data Model" src="https://github.com/user-attachments/assets/8d3659d1-a135-4fbe-aea0-9c47ab28b95a" /> 

---

## Data Dictionary 
<img width="560" height="438" alt="image" src="https://github.com/user-attachments/assets/c923707b-3571-4239-a75f-cd33e85c8e61" />
<img width="544" height="493" alt="image" src="https://github.com/user-attachments/assets/eb2e0c62-64a9-4b38-b0d9-d2e596715584" />
<img width="558" height="522" alt="image" src="https://github.com/user-attachments/assets/11800135-b724-40ec-9e0c-c2ea15b53ab1" />



## Queries


| Feature                | Query 1 | Query 2 | Query 3 | Query 4 | Query 5 | Query 6 | Query 7 | Query 8 | Query 9 | Query 10 |
|------------------------|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:--------:|:--------:|
| multiple table join     |    X    |    X    |    X    |    X    |         |    X    |    X    |    X    |    X     |          |
| subquery               |         |         |         |         |    X    |         |         |         |          |          |
| GROUP BY              |    X    |    X    |    X    |    X    |         |         |         |         |          |          |
| GROUP BY with HAVING   |         |    X    |    X    |    X    |         |         |         |         |          |          |
| multi condition WHERE  |    X    |         |         |         |         |    X    |         |    X    |          |          |
| built-in functions     |    X    |    X    |    X    |    X    |    X    |         |         |         |    X     |          |
---

