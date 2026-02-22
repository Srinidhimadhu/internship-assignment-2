# HTML Authentication System POC

## Description

A simple Proof of Concept (POC) for an authentication system built using plain HTML only. No CSS, no JavaScript, and no backend — just basic HTML structure with anchor tag navigation to demonstrate a typical authentication flow.

## HTML Pages

| File | Description |
|------|-------------|
| `login.html` | Login page with Email and Password fields |
| `register.html` | Registration page with Name, Email, Password, and Confirm Password fields |
| `forgot-password.html` | Forgot Password page to request a password reset link |
| `reset-password.html` | Reset Password page to set a new password |
| `dashboard.html` | Dashboard page shown after a successful login |

## How to Run

1. Download or clone this project to your local machine.
2. Open the `login.html` file in any web browser.
3. Use the anchor links on each page to navigate through the authentication flow.

## Navigation Flow

```
login.html
  ├── --> register.html --> login.html
  ├── --> forgot-password.html --> reset-password.html --> login.html
  └── --> dashboard.html --> (logout) --> login.html
```

## Notes

- This is a static HTML-only POC with no real authentication logic.
- All navigation is handled via `<a>` anchor tags.
- No CSS styling, JavaScript, or form submission is used.
