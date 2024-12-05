- Add a new employee with all the details
  
  ```
   INSERT INTO employee (id, name, role, salary, age, address, phone) VALUES (101, "Rohit", "employee", 9000, 38, "home", 5554887770); 
 <div>
    <img src= "https://github.com/user-attachments/assets/b0cacc80-61a8-4261-86df-520d049e1f5f"  height =300px>

  </div>
  
- Retrieve all employee information:

  ```
  SELECT * FROM employee;
<div>
    <img src= "https://github.com/user-attachments/assets/6f63ef17-4cb1-4e94-a139-608213304fb8"  height =300px>

  </div>

- Get specific columns
  
   ```
  SELECT name, salary FROM employee;

<div>
    <img src= "https://github.com/user-attachments/assets/fd303db2-1e83-4ced-8fa9-0c0eb1dab7a6"  height =300px>

  </div>

- Find employees with a particular role

  ```
  SELECT * FROM employee WHERE role = "manager";

<div>
    <img src= "https://github.com/user-attachments/assets/46546a3a-230f-4c0f-bf3c-8ef936702212"  height =300px>

  </div>

- Search for employees with names containing

  ```
  SELECT * FROM employee WHERE name LIKE "A%";

<div>
    <img src= "https://github.com/user-attachments/assets/22c8c25e-1393-40d3-9018-7833387ac835"  height =300px>

  </div>

- Find employees older than 30 and earning more than $70,000:

  ```
  SELECT * FROM employee WHERE age > 30 AND salary > 70000;

<div>
    <img src= "https://github.com/user-attachments/assets/43c06cee-d5dd-41e4-be12-0d28e82380c6"  height =300px>

  </div>

- Change the salary of an employee with ID 100:

  ```
  UPDATE employee SET salary = 100000 WHERE id = 100;
  SELECT * FROM employee WHERE id = 100;

<div>
    <img src= "https://github.com/user-attachments/assets/0dd68d5a-4c52-480c-9775-3d1cebbf2ae3"  height =300px>

  </div>


- Update the address for employees in the 'boss' role:

  ```
  UPDATE employee 
  SET address = "75 ganshyam"
  WHERE role = "boss" AND id=1;
  SELECT * FROM employee WHERE role = "boss" AND id = 1;


<div>
    <img src= "https://github.com/user-attachments/assets/96d73b9e-b8a8-4e93-8507-d359ceb38140"  height =300px>

  </div>



- Remove an employee with ID 101:

  ```
  DELETE FROM employee WHERE id = 101;

<div>
    <img src= "https://github.com/user-attachments/assets/7667e346-6290-4c01-9b92-5b961b33c1f3"  height =300px>

  </div>





- Delete all employees under 20:

  ```
  DELETE FROM employee WHERE age <= 20;


<div>
    <img src= "https://github.com/user-attachments/assets/e6af7161-0acd-474b-af67-6672fb8283f3"  height =300px>

  </div>




