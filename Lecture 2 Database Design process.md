

---

# **Database Design Process**

## **What is Database Design?**

Database Design is the process of planning and organizing data before creating a database.

**Simple Definition:**

> **Database Design is the process of deciding how data will be stored, organized, and connected in a database.**

### **Example**

Imagine you are creating a **University Database**.

Instead of randomly storing information, you first decide:

* What data is needed?
* How will it be stored?
* How are different data connected?

This planning is called **Database Design**.

---

# **Why Do We Need Database Design?**

Without proper design:

* Data becomes messy.
* Duplicate data is stored.
* Searching becomes slow.
* Updating data becomes difficult.
* More storage is wasted.

A good database design makes the database:

* Organized
* Fast
* Secure
* Easy to maintain

---

# **Database Design Process (Steps)**

There are **6 main steps** in database design.

---

## **Step 1: Requirement Analysis**

### What happens?

First, understand what the client or organization needs.

Ask questions like:

* What information should be stored?
* Who will use the database?
* What reports are needed?
* What operations will be performed?

### Example

For a School Database:

Need to store:

* Student Information
* Teacher Information
* Courses
* Marks
* Attendance

---

## **Step 2: Identify Entities**

An **Entity** is a real-world object about which we store information.

### Examples

* Student
* Teacher
* Course
* Department
* Library Book

For a school database:

Entities are:

* Student
* Teacher
* Course

---

## **Step 3: Identify Attributes**

Attributes describe an entity.

### Example

**Student**

Attributes:

* Student ID
* Name
* Age
* Email
* Phone Number

Another example:

**Course**

Attributes:

* Course ID
* Course Name
* Credit Hours

---

## **Step 4: Define Relationships**

Now connect the entities.

Ask:

> How are these entities related?

### Example

A Student enrolls in a Course.

Teacher teaches a Course.

Department has many Teachers.

Relationship examples:

* Student → Course
* Teacher → Course
* Department → Teacher

---

## **Step 5: Create ER Diagram**

ERD stands for **Entity Relationship Diagram**.

It is a visual representation of the database.

It shows:

* Entities
* Attributes
* Relationships

### Example

```
Student -------- Enrolls -------- Course

Student
---------
Student_ID
Name
Email

Course
---------
Course_ID
Course_Name
Credit_Hours
```

---

## **Step 6: Normalize the Database**

Normalization removes unnecessary duplicate data.

Benefits:

* Less redundancy
* Better consistency
* Easy updates
* Better performance

Example:

Instead of writing

```
Student Name
Course Name
Teacher Name
Teacher Office
```

again and again,

store Teacher information only once in the Teacher table.

---

# **Final Database Design**

After completing all steps:

* Create Tables
* Define Primary Keys
* Define Foreign Keys
* Add Constraints
* Test the database

Then the database is ready for implementation.

---

# **Real-Life Example**

Suppose you are designing a **Hospital Database**.

### Step 1

Requirements:

Store

* Patients
* Doctors
* Appointments
* Medicines

---

### Step 2

Entities

* Patient
* Doctor
* Appointment
* Medicine

---

### Step 3

Attributes

**Patient**

* Patient_ID
* Name
* Age
* Phone

**Doctor**

* Doctor_ID
* Name
* Specialization

---

### Step 4

Relationships

Patient books Appointment.

Doctor attends Appointment.

Doctor prescribes Medicine.

---

### Step 5

Draw ER Diagram.

---

### Step 6

Normalize the database.

---

# **Easy Analogy**

Think of building a house:

1. Decide what kind of house you need (**Requirement Analysis**)
2. Draw the rooms (**Entities**)
3. Decide what each room contains (**Attributes**)
4. Connect the rooms with doors (**Relationships**)
5. Create the blueprint (**ER Diagram**)
6. Remove unnecessary things to make it efficient (**Normalization**)

Finally, you build the house (**Create the Database**).

---



