# Admin Mode - Teacher Credentials

This document contains the login credentials for testing the admin/teacher authentication system.

## Test Accounts

### Account 1 (Admin)
- **Username:** `admin`
- **Password:** `admin123`

### Account 2 (Teacher 1)
- **Username:** `teacher1`
- **Password:** `password123`

### Account 3 (Teacher 2)
- **Username:** `teacher2`
- **Password:** `password456`

## How to Use

1. Click the user icon (👤) in the top right corner of the page
2. Click the "Login" button in the dropdown menu
3. Enter one of the username/password combinations above
4. After logging in, you will be able to:
   - Register students for activities
   - Unregister students from activities (using the ❌ button next to each participant)

## Security Note

**Important:** This is a simplified authentication system for demonstration purposes only. In a production environment, you should:
- Use proper password hashing (bcrypt, argon2, etc.)
- Implement secure session management
- Use HTTPS for all communications
- Add CSRF protection
- Implement rate limiting on login attempts
- Use environment variables for sensitive data
- Never store passwords in plain text
