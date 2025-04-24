# Multimodal Authentication System 🔐

This **Multimodal Authentication System** leverages **face recognition** and **email-based OTP verification** to create a secure and efficient login process. Users can authenticate using their face, traditional credentials (username/password), and an additional **OTP sent to their email** for added security.

---

## 🚀 Features

- **Face Recognition Login**: Authenticate using facial features with real-time webcam capture.
- **Credential-Based Login**: Secure login using a username and password.
- **Email OTP Verification**: An OTP is sent to the user's email for extra verification during login.
- **User Registration**: Register new users with face data and credentials.
- **Admin Dashboard** (Optional): Admin access for managing user records and login attempts.
- **Cross-Platform**: Compatible with multiple operating systems.

---

## 🛠️ Tech Stack

- **Python** 3.8.10
- **OpenCV**: Library for real-time computer vision and video capture.
- **dlib**: A toolkit for face detection and recognition.
- **face_recognition**: Built on dlib, it provides an easy API for face recognition tasks.
- **Flask** (optional): If the system is web-based, Flask handles backend operations.
- **MySQL**: Stores user credentials and face data for recognition.
- **CMake**: Required to build `dlib` on some systems.
- **SMTP/Nodemailer**: For sending OTPs via email.

---



