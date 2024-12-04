# Create a DBMS for employees

## Add a new employee with all Details 

```dart
INSERT INTO employee (id,name,role,salary,age,address,phone) VALUES (107,"Rahul Mishra","Assistant Manager",47000,44,"87 Narayan Nagar Valsad",85896340011)
```
<p>
   <img src="https://github.com/user-attachments/assets/4784208b-6b29-44fa-8b12-b0d7d0ab47c5"height="350">

</p>

## Retrieve all employee information:

```dart
SELECT * FROM employee;
```
<p>
   <img src="https://github.com/user-attachments/assets/6084cf99-69ed-48b3-8c89-9c30b52639b3"height="350">

</p>

## Get specific columns for all employees (e.g., name, salary):

```dart
SELECT name, salary FROM employee;
```
<p>
   <img src="https://github.com/user-attachments/assets/70a539c6-fef3-4892-b7c3-94a793de6796"height="350">

</p>

## Find employees with a specific role (e.g., Manager):

```dart
SELECT * FROM employee WHERE role = 'Manager';
```
<p>
   <img src="https://github.com/user-attachments/assets/295e2c85-41b4-46a4-8d59-b80f49632654 "height="350">

</p>

## Find employees older than 30 and earning more than $70,000:

```dart
SELECT * FROM employee WHERE age > 30 AND salary > 70000;
```
<p>
   <img src="https://github.com/user-attachments/assets/9e0ba49a-fb2a-4400-922e-3940a4035a32"height="350">

</p>

## Change the salary of an employee with ID 101:

```dart
UPDATE employee SET salary = 35000 WHERE id = 101;
```
<p>
   <img src="https://github.com/user-attachments/assets/ffeb6342-fe73-4a1d-8c44-bf6ddd119573"height="350">

</p>

## Remove an employee with ID 101:

```dart
DELETE FROM employee WHERE id = 101;
```
<p>
   <img src="https://github.com/user-attachments/assets/b9cf6670-63ae-4d43-b734-d72f744eb59c"height="350">

</p>

## Delete all employees with age less than 35 (assuming it's not a valid age):

```dart
DELETE FROM employee WHERE age < 35;
```
<p>
   <img src="https://github.com/user-attachments/assets/09e26f40-bf6b-4b16-ba7e-18dfcda9245c"height="350">

</p>
