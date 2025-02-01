
# Mess Management Application 

## Overview
A mess management app for bachelors to track expenses, manage meals, and automate cost calculations with online payment integration.

## Features
### 1. User Authentication
- Sign Up / Sign In / Password Reset
- Profile Management

### 2. Dashboard
- Overview of expenses and attendance
- Manager selection
- Meal cost calculations

### 3. User Roles & Permissions
#### **Admin**
- Create mess
- Invite & approve members
- Assign managers
- View cost details & member history

#### **Manager**
- Set & approve menu
- Manage meal attendees
- Track expenses & funds
- Organize special menu events

#### **Attendee**
- View menu wishlist
- Log individual/group expenses
- Mark meal attendance
- View expense reports

### 4. Expense & Cost Management
- Daily cost entry
- Automated per-head meal calculation
- End-of-month cost distribution

### 5. Payment Integration
- Online payment (bKash, Nagad, Bank Transfer)
- Auto-generated invoices
- Payment reminders

### 6. Notification System
- Meal reminders
- Monthly cost summaries
- Announcements

## Wireframe Design
Includes:
1. **Login & Signup Page**
2. **Dashboard (Admin, Manager, Member)**
3. **Expense Entry Form**
4. **Meal Attendance Page**
5. **Online Payment Interface**
6. **Notifications Page**

---

## Technical Diagram 






```mermaid
graph TD;
  A["<b style='font-size:16px; color:#FF5733'>User Authentication</b>"] -->|Sign Up / Sign In| B["<b style='font-size:16px; color:#33FF57'>Dashboard</b>"];
  B --> C["<b style='font-size:16px; color:#3357FF'>Expense & Cost Management</b>"];
  B --> D["<b style='font-size:16px; color:#FF33A1'>Payment Integration</b>"];
  B --> E["<b style='font-size:16px; color:#FFD700'>Notification System</b>"];
  C -->|Daily Cost Entry| C1["<b style='font-size:14px; color:#FF4500'>Automated Calculation</b>"];
  C -->|End-of-month Summary| C2["<b style='font-size:14px; color:#8A2BE2'>Cost Distribution</b>"];
  D -->|bKash, Nagad, Bank Transfer| D1["<b style='font-size:14px; color:#00CED1'>Invoice Generation</b>"];
  D -->|Payment Reminders| D2["<b style='font-size:14px; color:#DC143C'>Notifications</b>"];
  E -->|Meal Reminders| E1["<b style='font-size:14px; color:#32CD32'>User Alerts</b>"];
  E -->|Cost Summaries| E2["<b style='font-size:14px; color:#FFD700'>Monthly Reports</b>"];
  A -->|Profile Management| F["<b style='font-size:16px; color:#FF8C00'>User Roles</b>"];
  F -->|Admin| G["<b style='font-size:14px; color:#FF1493'>Manage Mess & Members</b>"];
  F -->|Manager| H["<b style='font-size:14px; color:#1E90FF'>Set Menu & Track Expenses</b>"];
  F -->|Attendee| I["<b style='font-size:14px; color:#228B22'>View & Log Expenses</b>"];


  ```
