# Student Login & Registration System

This is my submission for the SE104 HTML forms assignment. It demonstrates a basic frontend authentication flow.

## Project Files

- `index.html` - Main entry point (Login page)
- `register.html` - User registration form
- `server.html` - Mock success page (acts as form submission target)
- `instructions.html` - Helper text loaded into an iframe
- `styles.css` - Main stylesheet

## Key Features

### Login (index.html)
- Simple username/password auth form
- Links to registration if user has no account

### Registration (register.html)
- Full data collection form (Name, Email, Gender, etc.)
- Includes an iframe at the bottom that displays the server response after submit

## Setup & Running

1. Clone or download this repo.
2. Open `index.html` in Chrome, Firefox, or Edge.
3. No local server needed, it runs directly in the browser.

## Notes for Grader
- **Important:** Forms use `method="GET"` for maximum compatibility with static hosting environments (like viewing directly from disk or basic live servers) where `POST` requests might be blocked.
- I used `target="result_frame"` on the registration form so the success message loads in the iframe without navigating away from the main page.