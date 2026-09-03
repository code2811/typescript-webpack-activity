# Web Storage Activity

Simple classroom project for cookies, local storage, session storage, and basic security checks.

## Run

```bash
npm install
npm start
```

Open http://localhost:3000/login.html

If `npm start` fails, make sure terminal is inside this folder:

```bash
cd c:\Users\hp\Documents\Fullstack_course\web-storage-activity-web-storage-1
```

## Pages

- `public/login.html`:
  login form, CSRF token, server cookie login
- `public/app.html`:
  theme preference, session cart, sanitize input demo
- `public/reflection.html`:
  comparison table and discussion answers

## Assignment coverage

- Cookies:
  server sets `authToken` with HttpOnly, Secure (production), and 7-day expiry, logout clears cookie
- Local storage:
  saves user settings with `JSON.stringify` / `JSON.parse`
- Session storage:
  temporary cart data for the current session
- Security:
  CSRF token check on login and `encodeURIComponent` sanitization demo
- Reflection:
  required table and short answers included

## Submission note

Use this repo URL for GitHub Classroom and attach the required PDF form.
