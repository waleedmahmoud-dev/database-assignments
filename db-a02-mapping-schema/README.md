# Assignment - Relational Mapping

## Overview

This assignment focuses on transforming database requirements into a complete relational schema.

Each problem was analyzed and converted into relational tables with:

- Primary Keys
- Foreign Keys
- Junction Tables for M:N relationships
- Composite Keys where required
- Proper constraint handling

---

# Relational Mapping Summary

---

## ✅ Problem 1 – ITI Students System

### Tables

- Students
- Departments
- Courses
- Instructors
- Topics
- Student_Course (includes Grade)
- Instructor_Course (includes Evaluation)

### Mapping Logic

- 1:M relationships implemented using Foreign Keys.
- M:N relationships resolved using junction tables.
- Department manager stored using Manager_ID in Departments.
- Topic_ID stored as FK in Courses.

---

## ✅ Problem 2 – Musicana Records

### Tables

- Musicians
- Instruments
- Albums
- Songs
- Musician_Instrument
- Musician_Song

### Mapping Logic

- M:N relationships handled using associative tables.
- Album_ID stored in Songs (each song belongs to one album).
- Producer_ID stored in Albums referencing Musicians.

---

## ✅ Problem 3 – Real Estate Firm

### Tables

- Sales_Offices
- Employees
- Properties
- Owners
- Property_Owner (includes Ownership_Percentage)

### Mapping Logic

- Employees assigned to one Sales Office via FK.
- Manager relationship implemented in Sales_Offices.
- Property_Owner resolves M:N and stores ownership percentage.

---

## ✅ Problem 4 – General Hospital

### Tables

- Wards
- Patients
- Consultants
- Nurses
- Drugs
- Patient_Consultant
- Drug_Administration

### Mapping Logic

- Patients linked to Ward via FK.
- Leading consultant stored in Patients.
- M:N examination handled via Patient_Consultant.
- Drug_Administration stores dosage, date, and time.
- Nurse–Ward relationship enforced as 1:1.

---

## ✅ Problem 5 – Airline Database

### Tables

- Airlines
- Employees
- Aircraft
- Routes
- Crew
- Aircraft_Route
- Transactions

### Mapping Logic

- Airline_ID stored in Employees and Aircraft.
- Aircraft_Route resolves M:N and stores route-specific attributes.
- Crew linked 1:1 with Aircraft.
- Transactions linked to Airline.

---

# Concepts Applied

- 1:1 Relationship Mapping
- 1:M Relationship Mapping
- M:N Relationship Resolution
- Junction Tables
- Composite Primary Keys
- Foreign Key Constraints
- Associative Entities with Attributes
- Logical Schema Design
