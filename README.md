## 1. Create database named: FacultySystemDB. 
![Q1](lab1/lab1-1.png)

## 2. Create collection (student) that has:
	● FirstName: string, LastName: string, Age: Number, Faculty: An object that
	has Name and Address
	● Grades: An array of objects, each object has: CourseName, Grade, Pass
	(Boolean).
	● IsFired: Boolean
 ![Q2](lab1/lab1-2.png)

## 3. Insert 3 (at least) documents in Student collection with different values.
	● Try inserting one record each time
	● Try inserting many students using one insert statement.
 ![Q3 1](lab1/lab1-3.png)
![Q3 0](lab1/lab1-3-3.png)

## 4. Retrieve the following data:
	● All Students.
	● Student with specific First Name.
	● Students who his First Name=Ahmed, or Last Name= Ahmed.
	● Students that their First name isn't "lola".
	● Students with Age more than or equal to 21, and their faculty isn't NULL.
	● Display student with specific First Name, and display his First Name, 
	  Last name, IsFired fields only.
   ![Q4 0](lab1/lab1-4.png)
![Q4 5](lab1/lab1-5.png)
![Q4 4](lab1/lab1-6.png)
![Q4 3](lab1/lab1-7.png)
![Q4 2](lab1/lab1-8.png)
![Q4 1](lab1/lab1_9.png)

## 5. Update the student with specific FirstName, and change his LastName.
![Q5](lab1/lab1-10.png)

## 6. Delete Fired students.
![Q6](lab1/lab1-11.png)

## 7. Delete all students collection.
![Q7](lab1/lab1-12.png)

## 8. Delete the whole DB.

![Q8](lab1/lab1-13.png)
## - Import inventory database.

![Q1](lab2/lab2_1.png)
![Q1](lab2/lab2_1output.png)

## - Display number of products per category.

![Q1](lab2/lab2_2.png)

## - Display max category products price.

![Q1](lab2/lab2_3.png)

## - Display user ahmed orders populated with product.

![Q1](lab2/lab2_4_1.png)
![Q1](lab2/lab2_4_2.png)
![Q1](lab2/lab2_4_3.png)
![Q1](lab2/lab2_4_4.png)
![Q1](lab2/lab2_4_5.png)


## - Get user ahemd highest order price

![Q1](lab2/lab2_5.png)


## - import books.json.


![Q1](lab2/lab2_6.png)
![Q1](lab2/lab2_6_2.png)

## - Running aggregation queries that use multiple stages ($match, $group, $count, $skip, $limit, $lookup, $sortByCount etc).

*filter books with more than 600 pages*

![Q1](lab2/lab2_7.png)

*the total number of books in each category*
![Q1](lab2/lab2_8.png)

*count the total number of books*
![Q1](lab2/lab2_9.png)
