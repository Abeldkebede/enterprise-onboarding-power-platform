# Dataverse Tables

## Employee

| Column | Type |
|----------|----------|
| EmployeeID | Auto Number |
| FirstName | Text |
| LastName | Text |
| Email | Text |
| Department | Lookup |
| Manager | Lookup |

## Department

| Column | Type |
|----------|----------|
| DepartmentID | Auto Number |
| DepartmentName | Text |

## Equipment

| Column | Type |
|----------|----------|
| AssetID | Auto Number |
| DeviceType | Text |
| AssignedEmployee | Lookup |
| Status | Choice |
