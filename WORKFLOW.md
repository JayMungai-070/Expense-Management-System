# Expense Manager System Workflows

## 1. Authentication Workflows

### 1.1 Registration Process
1. User visits the landing page
2. Clicks "Get Started" button
3. Fills registration form with:
   - Username
   - Email
   - Password
   - Password confirmation
4. System validates:
   - Email format
   - Password strength
   - Unique email check
5. Creates new user account
6. Redirects to login page

### 1.2 Login Process
1. User visits login page
2. Enters credentials:
   - Email
   - Password
3. System validates credentials
4. Creates user session
5. Redirects to dashboard

### 1.3 Logout Process
1. User clicks logout
2. System destroys session
3. Redirects to landing page

## 2. Expense Management Workflows

### 2.1 Adding New Expense
1. From dashboard, click "Add Expense"
2. Fill expense details:
   - Amount
   - Category
   - Date
   - Description
   - Receipt (optional)
3. System validates input
4. Saves to database
5. Updates dashboard totals

### 2.2 Editing Expense
1. Locate expense in list
2. Click edit icon
3. Modify desired fields
4. Save changes
5. System updates records

### 2.3 Deleting Expense
1. Locate expense
2. Click delete icon
3. Confirm deletion
4. System removes record
5. Updates totals

## 3. Category Management Workflows

### 3.1 Creating Categories
1. Navigate to Categories
2. Click "Add Category"
3. Enter:
   - Category name
   - Description (optional)
   - Color code (optional)
4. System saves category

### 3.2 Managing Categories
1. View all categories
2. Options:
   - Edit category details
   - Delete category
   - View category expenses

## 4. Reporting Workflows

### 4.1 Generating Reports
1. Access Reports section
2. Select report type:
   - Monthly summary
   - Category-wise
   - Date range
   - Custom
3. Set parameters:
   - Date range
   - Categories
   - Report format
4. Generate report

### 4.2 Analyzing Data
1. View visual representations:
   - Pie charts
   - Bar graphs
   - Line trends
2. Export options:
   - PDF
   - CSV
   - Excel

## 5. Profile Management Workflows

### 5.1 Updating Profile
1. Access Profile section
2. Modify:
   - Personal information
   - Email
   - Profile picture
3. Save changes

### 5.2 Password Change
1. Go to security settings
2. Enter:
   - Current password
   - New password
   - Confirm new password
3. System validates
4. Updates credentials

## 6. Dashboard Workflows

### 6.1 Overview Display
1. Shows:
   - Monthly total
   - Category breakdown
   - Recent transactions
   - Budget status

### 6.2 Quick Actions
1. Available actions:
   - Add expense
   - View reports
   - Manage categories
   - Search transactions

## 7. Data Validation Workflows

### 7.1 Input Validation
- Amount format check
- Date validation
- Required fields check
- File upload validation

### 7.2 Security Checks
- CSRF token validation
- Session verification
- Permission checks
- SQL injection prevention

## 8. Error Handling Workflows

### 8.1 User Errors
1. System displays:
   - Error message
   - Correction guidance
   - Recovery options

### 8.2 System Errors
1. Logs error details
2. Shows user-friendly message
3. Maintains data integrity
4. Provides support contact

## 9. Mobile Responsiveness

### 9.1 Interface Adaptation
- Responsive navigation menu
- Touch-friendly elements
- Optimized forms
- Flexible layouts

### 9.2 Mobile Features
- Swipe actions
- Touch gestures
- Mobile-optimized charts
- Responsive tables

## 10. Installation and Setup Guide

### How to run Expense Manager Application Using PHP and MySQL

1. Download the zip file
2. Extract the file and copy Expense Manager folder
3. Paste inside root directory (for xampp xampp/htdocs)
4. Open PHPMyAdmin (http://localhost/phpmyadmin)
5. Create a database with name expense_manager.db
6. Import db_sober.sql file(given inside the zip package in SQL file folder)
7. Run the script http://localhost/Expense Manager  (frontend)

### Default Login Credentials
- Email: test@mail.com
- Password: 12345678