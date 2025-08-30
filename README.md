# Employee Management System

## Description

Create a comprehensive web application that allows administrators to perform CRUD (Create, Read, Update, Delete) operations on employee records. The system features robust authentication mechanisms and proper validation to protect sensitive employee data. Built as a single-page application with modern UI/UX design, it provides an intuitive interface for managing employee information including personal details, department assignments, salary information, and employment status.

## Features

- **User Authentication**: Secure login system with session management
- **CRUD Operations**: Complete Create, Read, Update, Delete functionality for employee records
- **Data Validation**: Comprehensive client-side validation with real-time error feedback
- **Search Functionality**: Real-time search across employee names, departments, and positions
- **Statistics Dashboard**: Live statistics showing total employees, active count, and average salary
- **Responsive Design**: Mobile-friendly interface that works on all device sizes
- **Modern UI**: Beautiful gradient design with smooth animations and hover effects
- **Error Handling**: Graceful error handling with user-friendly error messages
- **Data Security**: Input sanitization and validation to prevent malicious data entry
- **Sample Data**: Pre-loaded with demonstration employee records

## Installation and Usage

1. Clone this repository:
   ```bash
   https://github.com/kruthickroshan99/PRODIGY_FS_02
   ```

2. Open the application:
   ```bash
   # Simply open the HTML file in your web browser
   open main.html
   ```

3. Login using the demo credentials and start managing employee records through the intuitive web interface.

## Demo Credentials

- **Username**: `admin`
- **Password**: `admin123`

## Screenshots

### Login Screen
(<img width="1919" height="911" alt="Screenshot 2025-08-30 140806" src="https://github.com/user-attachments/assets/57a87070-2523-4045-a6a0-0490ccf20e64" />
)

### Employee Management Form
(<img width="1918" height="911" alt="Screenshot 2025-08-30 140825" src="https://github.com/user-attachments/assets/88c0b875-4c28-469d-a793-58e3661ce238" />
)

### Add Employee Form
(<img width="1919" height="905" alt="Screenshot 2025-08-30 140854" src="https://github.com/user-attachments/assets/f5c03409-7058-44cc-8b3a-96b9b4fbd319" />
)

### Edit Employee Form
(<img width="1919" height="904" alt="Screenshot 2025-08-30 141246" src="https://github.com/user-attachments/assets/3120f7c2-ae4f-49f4-ae65-09aef3a45d36" />
)

## Technical Specifications

### Built With
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with gradients, animations, and responsive design
- **Vanilla JavaScript** - Pure JavaScript with no external dependencies
- **Local Storage** - Client-side data persistence (in-memory for demo)

### Validation Rules
- **Name Fields**: Minimum 2 characters required
- **Email**: Must be valid format and unique across all employees
- **Phone**: Optional but validated format when provided
- **Salary**: Minimum $1,000 required
- **Hire Date**: Cannot be in the future
- **Department**: Must select from predefined list

### Security Features
- Session-based authentication
- Input validation and sanitization
- XSS prevention through proper data handling
- Confirmation dialogs for destructive operations
