# Finals Lab Task 1. MySQL Basics Multi-Level Company
The following are the tasks that need to be implemented using MySQL statements. Make sure to complete them in the order specified:


## Task 1: Create a table named employees with the following fields:
employee id: Unique integer, auto-increment, primary key.
employee name: String (VARCHAR) with up to 255 characters, not null.
manager id: Integer, foreign key referencing employee id in the same table (employees).

## Task 2: Create a table named departments with the following fields:
department_id: Unique integer, auto-increment, primary key.
department_name: String (VARCHAR) with up to 255 characters, not null.

## Task 3: Create a table named employee departments with the following fields:
employee id: Integer, foreign key referencing employee id in employees.
department id: Integer, foreign key referencing department id in departments.
Composite primary key (employee id, department id).

## Task 4: Create a table named employee projects with the following fields:
employee id: Integer, foreign key referencing employee id in employees.
project name: String (VARCHAR) with up to 255 characters, not null.

## Task 5: Create a table named managers with the following fields:
manager id: Unique integer, auto-increment, primary key.
employee id: Integer, foreign key referencing employee_id in employees.



# Here's the Query Statement 

## 1. Employee Table.
![image](https://github.com/user-attachments/assets/0e91cb83-c7ab-415a-ba31-bd2a358e9609)


## 2. Department Table.
![image](https://github.com/user-attachments/assets/ea67a3dd-87a9-4edf-bd66-8e09b5cb9904)


## 3. Employee Dapartment Table.
![image](https://github.com/user-attachments/assets/0a6bcd94-d559-4855-93f2-d10c32c2b279)

## 4. Eployee Project Table. 
![image](https://github.com/user-attachments/assets/bb34e46f-4af1-4dff-b798-2eac74b98ec2)


## 5. Manager Table. 
![image](https://github.com/user-attachments/assets/508271f4-050b-4e92-938f-711a0558e0f8)



# Here's the Table Structure 

## 1. Employee Table.
![image](https://github.com/user-attachments/assets/222fdb7e-8609-4564-823f-37f4ba5605cf)


## 2. Dapertment Table.
![image](https://github.com/user-attachments/assets/29cf7978-ecb2-4d2d-8123-4ee03b449715)


## 3. Employee Dapartment Table.
![image](https://github.com/user-attachments/assets/44a606d5-c1aa-4a18-a6a7-8d7f809c591d)


## 4. Eployee Project Table. 
![image](https://github.com/user-attachments/assets/add18411-d935-496a-a30a-a71cdb639bf3)


## 5. Manager Table. 
![image](https://github.com/user-attachments/assets/d2f8b798-debb-4d60-9b46-29d95176337f)


# EER Diagram 
![image](https://github.com/user-attachments/assets/7cb889e9-5320-4416-a9b5-d8938f022e7d)


# SQL code
![image](https://github.com/user-attachments/assets/4676af8b-49d7-45aa-8c7e-c4ba8d6d0d1f)
![image](https://github.com/user-attachments/assets/8418d152-26dd-451f-8d28-8cfeada8115e)



[BACK TO PORTFOLIO](https://zomue.github.io/)
