# Login & Registration System

A simple HTML forms project with login and registration pages.

## Project Structure

```
project/
├── login.html          # Login page with username and password
├── register.html       # Registration page with detailed form
├── server.html         # Success/thank you page
├── instructions.html   # Instructions page (shown in iframe)
├── styles.css          # Stylesheet for all pages
└── readme.md          # This file
```

## Features

### Login Page (`login.html`)
- Username input field
- Password input field
- Submit button
- Link to registration page

### Registration Page (`register.html`)
- Three text fields for name (Username, First Name, Last Name)
- Email field
- Email confirmation field
- Password field
- Gender selection (Radio buttons: Male/Female)
- Instructions section displayed in iframe
- Submit button sends data to `server.html` which displays in the same iframe

### Instructions Page (`instructions.html`)
- Displayed in iframe below the registration form
- Contains guidelines for filling the form
- Privacy notice

### Server Page (`server.html`)
- Displays success message after form submission
- Shown in iframe on registration page
- Link to return to login page

## How to Use

1. Download all files to your computer
2. Keep all files in the same folder
3. Open `login.html` in your web browser to start
4. Or open `register.html` to go directly to registration

## Form Methods

- **Login form**: Uses GET method (for demonstration)
- **Registration form**: Uses POST method and displays result in iframe

## Technologies Used

- HTML5
- CSS3 (with gradients and modern styling)
- No JavaScript required (pure HTML/CSS)

## Browser Compatibility

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Notes

- All form fields are required
- Email validation is handled by HTML5 `type="email"`
- Password fields use `type="password"` for security
- Radio buttons require selection before submission
- Forms use iframe target to display results

## License

Free to use for educational purposes.

---

Created for SE104 Course Assignment