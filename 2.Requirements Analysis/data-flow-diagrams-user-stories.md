# Data Flow Diagrams and User Stories

## 1. Introduction

The Requirements Analysis Phase focuses on understanding how data flows within the system and identifying user interactions. For the FitHub CRM (Salesforce-based Fitness Center Management System), this phase ensures that all system functionalities are clearly defined before development.

This document includes:

- Data Flow Diagrams (DFD)
- User Stories representing system users

---

## 2. Data Flow Diagram (DFD)

A Data Flow Diagram (DFD) visually represents how data moves through the system, showing inputs, processes, storage, and outputs.

---

## DFD Level 0 (Context Diagram)

The Level 0 DFD represents the system as a single process interacting with external entities.

### External Entities

- Member
- Trainer
- Admin

### System

- FitHub CRM System

### Data Flow

- Members provide registration details
- Admin manages data
- Trainers update availability

---

## DFD Level 1 (Detailed View)

The Level 1 DFD breaks the system into multiple processes.

### Processes

1. Member Registration
2. Membership Management
3. Trainer Assignment
4. Payment Processing
5. Notification System

### Data Stores

- Member Database
- Trainer Database
- Payment Records
- Scheduling Data

### Data Flow Explanation

- Member registers → Data stored in database
- Admin updates schedules → Trainers assigned
- Payment processed → Record updated
- Notification sent → Member informed

---

## 3. User Stories

User stories describe system functionalities from the perspective of different users.

---

## Member User Stories

- As a member, I want to register easily so that I can access gym services
- As a member, I want to receive notifications for membership expiry
- As a member, I want to book fitness classes

---

## Admin User Stories

- As an admin, I want to manage member records
- As an admin, I want to assign trainers based on availability
- As an admin, I want to generate reports

---

## Trainer User Stories

- As a trainer, I want to update my availability
- As a trainer, I want to view assigned sessions
- As a trainer, I want to manage schedules

---

## 4. Functional Insights from User Stories

From the user stories, the following system functionalities are derived:

- User Authentication
- Membership Management
- Trainer Scheduling
- Payment Processing
- Notification System

---

## 5. Importance of DFD and User Stories

- Helps in understanding system workflow
- Identifies user requirements clearly
- Reduces development errors
- Ensures better system design

---

## 6. Conclusion

The Data Flow Diagram and User Stories provide a clear understanding of how the FitHub CRM system will function. This ensures that all stakeholders have a common understanding of the system requirements before development begins.