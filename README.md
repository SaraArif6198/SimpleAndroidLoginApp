# 🔐 LoginApp

A simple **Android login application** with "Remember Me" functionality. Users can enter their email and password, choose to remember their credentials, and receive feedback on successful or failed login attempts.

[![Java](https://img.shields.io/badge/Language-Java-orange)](https://www.java.com/)
[![Android SDK](https://img.shields.io/badge/Android%20SDK-yes-brightgreen)](https://developer.android.com/studio)
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)

---

## ✨ Features

- **Email and Password login:** Users can enter email and password to log in.  
- **Remember Me:** Save user credentials locally using `SharedPreferences` when the checkbox is selected.  
- **Input Validation:** Checks for empty email or password fields.  
- **User Feedback:** Displays Toast messages for successful login or invalid credentials.  
- **Edge-to-Edge UI:** Proper padding for modern Android devices using `WindowInsets`.  

---

## 🖼 Screenshots

*(Add screenshots of the login screen for better visualization.)*

<table>
<tr>
<td>

**Login Screen**<br>
<img src="https://via.placeholder.com/300x600.png?text=Login+Screen" width="300"/>

</td>
</tr>
</table>

---

## ⚙ How It Works

### 1. MainActivity
- Users input their **email** and **password**.  
- If the **"Remember Me"** checkbox is selected, the credentials are saved locally using `SharedPreferences`.  
- Input fields are validated to ensure they are not empty.  
- Predefined credentials (`sara@gmail.com` / `1234`) are used for login authentication.  

### 2. SharedPreferences
- Stores email, password, and remember state.  
- If "Remember Me" was previously checked, the saved credentials are automatically restored when the app launches.  

### 3. Edge-to-Edge Layout
- Uses `WindowInsets` to add padding for system bars and avoid UI overlap on modern devices.

---

## 🛠 Usage

1. Open the project in **Android Studio**.  
2. Build and run the app on an emulator or physical device.  
3. Enter the predefined credentials:  
   - **Email:** `sara@gmail.com`  
   - **Password:** `1234`  
4. Optionally check **"Remember Me"** to save credentials.  
5. Tap **Login** to authenticate and see the corresponding Toast message.  

---

## 💻 Technologies Used

- Java  
- Android SDK  
- Android Studio  
- `SharedPreferences` for local storage  
- ConstraintLayout and modern UI practices  

---

## 📌 Notes

- Only the predefined credentials are valid for login.  
- The "Remember Me" functionality ensures a smoother experience for returning users.  
- Edge-to-Edge support ensures compatibility with devices with display cutouts and navigation bars.  

---

## 👩‍💻 Author

**Sara Arif** – Developed as part of an Android learning project.  
[LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/)
