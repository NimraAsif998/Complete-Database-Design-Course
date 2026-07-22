# Entities, Attributes & Relationships 

## Introduction

Before creating a database, we need to understand **what data will be stored**, **what information will be stored about that data**, and **how different data is connected**. These concepts are represented using the **Entity-Relationship (ER) Model**, which helps us design a database before implementation.

The ER Model consists of three main components:

* **Entity**
* **Attribute**
* **Relationship**

---

# 1. What is an Entity?

### Definition

An **Entity** is any real-world object, person, place, event, or thing about which data is stored in a database.

**Simple Definition:**

> **Entity = Anything for which we want to store information in the database.**

### Examples

* Student
* Teacher
* Employee
* Customer
* Product
* Book
* Department

---

### Real-Life Example

Consider a **University Database**.

The entities could be:

* Student
* Teacher
* Course
* Department

Each entity has its own records stored in the database.

---

# 2. What is an Attribute?

### Definition

An **Attribute** is a property or characteristic that describes an entity.

**Simple Definition:**

> **Attribute = Information or details about an entity.**

---

### Example

**Entity:** Student

**Attributes:**

* Student_ID
* Name
* Age
* Gender
* Email
* Phone Number

These attributes describe a student.

---

### Another Example

**Entity:** Product

**Attributes:**

* Product_ID
* Product_Name
* Price
* Quantity
* Brand

---

# 3. Types of Attributes

## 1. Simple Attribute

A simple attribute cannot be divided into smaller parts.

**Examples:**

* Age
* Gender
* Salary

---

## 2. Composite Attribute

A composite attribute can be divided into multiple sub-parts.

**Examples:**

**Name**

* First Name
* Middle Name
* Last Name

**Address**

* House Number
* Street
* City
* Postal Code

---

## 3. Single-Valued Attribute

An attribute that has only one value for each entity.

**Examples:**

* Student_ID
* CNIC
* Blood Group

---

## 4. Multi-Valued Attribute

An attribute that can have more than one value.

**Examples:**

* Phone Numbers
* Email Addresses
* Skills
* Languages

---

## 5. Derived Attribute

An attribute whose value is calculated from another attribute.

**Examples:**

* Date of Birth → Age
* Joining Date → Experience

---

## 6. Key Attribute

An attribute that uniquely identifies each record in an entity.

**Examples:**

* Student_ID
* Employee_ID
* Product_ID
* CNIC

---

# 4. What is a Relationship?

### Definition

A **Relationship** shows how two or more entities are connected with each other.

**Simple Definition:**

> **Relationship = An association or connection between two entities.**

---

### Example 1

**Student** → *Enrolls In* → **Course**

A student can enroll in one or more courses.

---

### Example 2

**Customer** → *Places* → **Order**

A customer places an order.

---

### Example 3

**Doctor** → *Treats* → **Patient**

A doctor treats patients.

---

# 5. Types of Relationships

## One-to-One (1:1)

One record of an entity is related to only one record of another entity.

**Example:**

Person → Passport

One person has one passport.

---

## One-to-Many (1:N)

One record of an entity is related to multiple records of another entity.

**Example:**

Teacher → Students

One teacher teaches many students.

---

## Many-to-One (N:1)

Multiple records of one entity are related to a single record of another entity.

**Example:**

Students → Department

Many students belong to one department.

---

## Many-to-Many (M:N)

Multiple records on both sides are related to each other.

**Example:**

Students ↔ Courses

A student can enroll in many courses, and a course can have many students.


