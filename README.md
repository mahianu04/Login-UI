## Flutter Login UI

This Flutter app is a **clean, elegant login UI** with:
- Custom background and container colors
- Shadow effects for depth
- Input fields with validation
- A dialog-based notification on login success/failure

---

### Features

* Modern and clean layout  
*  Email and password input fields with validation  
*  Password visibility toggle  
*  Login success/failure message as a dialog box  
*  Beautiful color palette with light blue background and soft shadows

---

### Dependencies

No third-party dependencies are needed beyond Flutter itself. The app uses the built-in Flutter `Material` components.

---

### 🔧 How It Works

#### Email & Password

- **Hardcoded credentials**:
    - Email: `user@gmail.com`
    - Password: `test123`

- The form checks:
    - If both fields are filled
    - If email follows proper format

#### Password Field
- Includes an **eye icon** to show/hide the password.

#### 🛉 Login Button
- Validates form
- If credentials match → shows a **“Login Successful”** dialog.
- Otherwise → shows a **“Login Failed”** dialog.
