# Password Authentication System 
## Year 11 Software Engineering

### Overview

This repository contains a Python implementation of a password authentication system that demonstrates how modern software systems securely store and verify user credentials.  
The project uses JSON files for data storage and applies industry-standard password security techniques including hashing, salting, and peppering.

Students will begin by working with a procedural implementation and then extend the project using Object-Oriented Programming (OOP) principles to create a complete CRUD (Create, Read, Update, Delete) user management system.

---

## Learning Intentions

By completing this project, students will:

* Understand the role of authentication in software systems.
* Implement secure password storage techniques.
* Apply hashing, salting, and peppering to protect user credentials.
* Read and write structured data using JSON files.
* Design and implement software using Object-Oriented Programming principles.
* Develop a complete CRUD application using Python.

---

## Success Criteria

Students can:

* Explain why plain-text password storage is insecure.
* Describe the difference between hashing and encryption.
* Create and verify user accounts using hashed passwords.
* Store and retrieve user data from a JSON file.
* Implement password changes and user deletion.
* Apply encapsulation and abstraction within an OOP solution.
* Test and evaluate the security of their implementation.

---

## Features

### Procedural Version

* Create user accounts
* Verify user passwords
* Store user data in a JSON file
* Hash passwords using bcrypt
* Apply password salting
* Apply password peppering

### OOP Extension

Students will implement:

* Create User
* View User(s)
* Change Password
* Delete User
* UserManager class
* File handling methods
* Password validation methods
* Authentication methods

---

## Security Concepts Covered

### Hashing

Passwords are never stored directly. Instead, they are converted into a unique hash value.

Example:

```text
Password123
↓
$2b$12$...
```

### Salting

A random salt is generated for each password before hashing.

Benefits:

* Prevents rainbow table attacks.
* Produces different hashes for identical passwords.

### Peppering

A secret pepper value is added to the password before hashing.

Benefits:

* Provides an additional layer of security.
* Keeps a secret value outside the database.

### Authentication

User authentication is performed by comparing the entered password against the stored hash using bcrypt.

---

## Example User Record

```json
{
  "johnsmith": {
    "hash": "$2b$12$...",
    "salt": "$2b$12$...",
    "created_at": "2026-06-14T10:30:00Z"
  }
}
```

---

### Programming and Software Development

Students:

* Design and implement software solutions using Python.
* Apply branching, iteration and functions.
* Develop and test software solutions.
* Use appropriate data structures and file storage techniques.

### Object-Oriented Programming

Students:

* Create classes and objects.
* Apply encapsulation.
* Design reusable software components.
* Organise code into methods and classes.

### Secure Software Development

Students:

* Investigate authentication methods.
* Implement password security techniques.
* Evaluate risks associated with storing user credentials.
* Apply secure coding practices.

### Data Management

Students:

* Store data using JSON files.
* Read and write structured data.
* Validate and manage user information.

---

## Extension Challenges

Students may extend the project by implementing:

* Password complexity rules.
* Login attempt limits.
* Password expiry dates.
---

### Teacher: Mr Solis

Year 11 Software Engineering

Password Authentication and User Management Project

Bossley Park High School

