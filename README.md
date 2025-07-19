# 🔐 FaceLock – Face Recognition Folder Locker for Windows

FaceLock is a Python-based facial recognition tool that locks and unlocks folders on Windows using a set face as the key. Instead of using passwords or PINs, FaceLock provides a seamless and secure way to access sensitive folders using real-time webcam authentication.

---

## 📸 Features

- 🧑‍💻 Face detection and recognition via webcam
- 🔐 Lock and unlock Windows folders based on identity
- 🧠 Easy setup with custom face data capture
- 💾 Secure face encoding storage
- 🪟 Windows-compatible folder hiding mechanism

---

## 🛠️ Technologies Used

- Python 3
- OpenCV
- face_recognition
- NumPy
- OS + ctypes

---

## 🔐 Folder Locking Logic

- When an unauthorized user is detected, the target folder is **locked** by hiding it using Windows attributes.
- When your face is recognized, the folder is **unlocked** and made visible again.
- The locking mechanism uses the `ctypes` library to apply the `+H +S` (Hidden + System) attributes on the folder.

---

## 👥 Contributors

- Niranjan Vijaya Krishnan
- Dominik Ritz
