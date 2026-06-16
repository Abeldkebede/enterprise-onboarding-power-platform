# Dataverse

Dataverse tables used by the Employee Onboarding Platform.

## Core Tables

### Employee
- Employee ID
- First Name
- Last Name
- Email
- Department
- Manager

### Department
- Department ID
- Department Name
- Cost Center

### Equipment Request
- Request ID
- Employee ID
- Device Type
- Approval Status

### Training Assignment
- Training ID
- Employee ID
- Due Date
- Completion Status

## Relationships

Employee → Department

Employee → Equipment Request

Employee → Training Assignment
