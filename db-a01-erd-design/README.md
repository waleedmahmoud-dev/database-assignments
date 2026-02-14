# Assignment - ERD Design

## Overview

This repository contains ERD designs for multiple real-world scenarios, each representing a different database problem. The problems include:

1. **ITI Course System**: Managing students, departments, courses, instructors, and topics, including grades and evaluations.
2. **Musicana**: Tracking musicians, instruments, albums, songs, and producers.
3. **Real Estate Firm**: Managing properties, sales offices, employees, owners, and property ownership percentages.
4. **General Hospital**: Managing wards, patients, consultants, nurses, and drugs administered to patients.
5. **Airlines Database**: Managing airlines, employees, aircraft, routes, crews, and buy/sell transactions.

Each problem includes the ERD design and represents a realistic scenario for database modeling.

## Requirements

The requirements are located in the requirements folder.

## Solution

The solution is located in the execution folder.

## Concepts

- Entities
- Attributes
- Relationships
- Keys


# Database ERD Problems Summary

---

## ✅ Problem 1 – ITI Students System

### Entities
- Students
- Departments
- Courses
- Instructors
- Topics

### Relationships
- Department contains Students
- Students take Courses
- Department includes Instructors
- Department managed by Instructor
- Instructors teach Courses
- Topics classify Courses

---

## ✅ Problem 2 – Musicana Records

### Entities
- Musicians
- Instruments
- Albums
- Songs

### Relationships
- Musicians play Instruments
- Albums contain Songs
- Musicians perform Songs
- Musicians produce Albums

---

## ✅ Problem 3 – Real Estate Firm

### Entities
- Sales Offices
- Employees
- Properties
- Owners

### Relationships
- Sales Office assigned Employees
- Employee manages Sales Office
- Sales Office lists Properties
- Owners own Properties

---

## ✅ Problem 4 – General Hospital

### Entities
- Wards
- Patients
- Consultants
- Nurses
- Drugs

### Relationships
- Ward hosts Patients
- Patient led by Consultant
- Patient examined by Consultant
- Nurse gives Drug to Patient
- Nurse supervises Ward
- Nurse serves in Ward

---

## ✅ Problem 5 – Airline Database

### Entities
- Airline
- Employees
- Aircraft
- Route
- Crew
- Transactions

### Relationships
- Airline owns Aircraft
- Aircraft assigned to Route
- Aircraft has Crew
- Airline records Transactions
- Airline employs Employees
