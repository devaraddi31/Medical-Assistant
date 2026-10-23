# 🏥 Government Hospital Finder

A simple, beginner-friendly frontend web application built using **plain HTML, CSS, and basic JavaScript**. It allows users to log in and search government health facilities across Indian districts using the open Esri India LivingAtlas Hospital Directory API.

---

## 📁 Project Structure

```
├── index.html        # Smart entry router (redirects to dashboard or login)
├── login.html        # Simple Login page (Username & Password validation)
├── dashboard.html    # Hospital search page with table results & logout
├── style.css         # Clean, responsive CSS styles
└── README.md         # Project documentation
```

---

## 🔑 Demo Login Credentials

- **Username:** `admin`
- **Password:** `admin123`

---

## 🚀 Key Features

1. **Simple Authentication:**
   - Validates user input (`admin` / `admin123`).
   - Uses `localStorage.getItem("isLoggedIn")` to maintain login session.
   - Redirects to `login.html` if user is not authenticated.
   - Simple `Logout` button to clear session.
2. **Live Hospital Search by District:**
   - Queries the open Esri India Hospital Directory REST API.
   - Shows loading state while searching.
   - Displays Facility Name, Address, PIN Code, Facility Type, District, and Phone Number in a clean table.
   - Stores recent searches in `localStorage`.

---

## 💻 How to Run

No installations or Node.js required!

1. Open the project folder.
2. Double-click **`index.html`** or **`login.html`** in any web browser (Chrome, Edge, Firefox).
3. Log in with `admin` and `admin123`.
4. Enter any district (e.g., `Bangalore`, `Mysore`, `Pune`, `Belagavi`) and click **Search Hospitals**.
