# Login Page Project

## 📖 Overview
This project is a simple **HTML, CSS, and JavaScript login page**.  
It demonstrates how to build a styled login form with client-side validation.  
The page checks credentials against hardcoded values and redirects to another page (`libri.html`) upon successful login.

---

## 🛠️ Features
- Responsive design with a gradient background.
- Centered login form with modern styling.
- Input fields for **username** and **password**.
- Client-side validation using JavaScript.
- Redirects to `libri.html` if login is successful.
- Displays alerts for success or invalid credentials.

---

## 📂 Project Structure

---

## 💻 How It Works
1. The login form collects **username** and **password**.
2. JavaScript function `checklogin()` validates input:
   - Correct username: `Siddharth`
   - Correct password: `12345678`
3. If credentials match:
   - Shows alert: *"Login Successful"*
   - Redirects to `libri.html`
4. If credentials are incorrect:
   - Shows alert: *"Invalid Credentials"*

---

## 🚀 Usage
1. Open `index.html` in a browser.
2. Enter:
   - **Username:** `Siddharth`
   - **Password:** `12345678`
3. On success, you’ll be redirected to `libri.html`.

---

## 🎨 Styling
- Gradient background (`orange → green`).
- White card-style login container with shadow.
- Smooth hover effects on the login button.
- Focus effects on input fields.

---

## ⚠️ Notes
- This is a **demo project**. Credentials are hardcoded and **not secure**.
- For real-world applications:
  - Use server-side authentication.
  - Store passwords securely (e.g., hashing).
  - Avoid plain-text credentials in JavaScript.

---

## 📌 Future Improvements
- Replace hardcoded credentials with a backend system.
- Add form validation (e.g., minimum password length).
- Implement session management.
- Enhance accessibility (ARIA labels, keyboard navigation).
