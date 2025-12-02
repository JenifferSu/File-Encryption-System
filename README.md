# 🔒 Mobile Application File Encryption System (Android)

**Developing a Secure Mobile Application for File Encryption and Data Protection**  
**Author:** *Jeniffer Su Kai Li*

 A **free, intuitive, and secure Android mobile application** for file encryption.  
The app enables individuals and small businesses to protect sensitive files (documents, images, videos) from unauthorized access—without the high cost or complexity of commercial solutions.

---

## 🚀 Get the App Now! (Direct Download)

If you just want to use the app, download the latest version below.

### 📥 Download the APK

| Version | Download Link | Notes |
|--------|----------------|--------|
| **v1.0.0** | **Download app-debug.apk** | Stable release |

> **Note:** Since this app is installed outside the Google Play Store, you may need to enable **“Install unknown apps”** in your device settings.

---

## ⚙️ Installation Guide (Sideloading)

1. **Download:** Click the `Download app-debug.apk` link above on your Android device.  
2. **Security Setting:** Go to **Settings > Security** (or **Apps & notifications > Special app access > Install unknown apps**).  
3. **Grant Permission:** Find the app used to download the APK (Chrome, Files App) and enable **Install unknown apps**.  
4. **Install:** Tap the downloaded `.apk` file to begin installation.  
5. **Open:** Once installed, open the app, register your secure account, and start encrypting your files!

---

## ✨ Key Features & Security Architecture

The app is built using a **layered architecture** (Presentation → Business Logic → Data Access → Storage → Security) to maximize confidentiality and reliability.

---

## 🛡️ Core Security Features

- **AES-256 Encryption:** Industry-standard AES-256 in CBC mode with PKCS5 Padding.  
- **Unique Keys:** A cryptographically secure unique key + IV are generated for **every file**.  
- **Secure Authentication:** User passwords are hashed with **SHA-256** before storing in SQLite.  
- **Local Security:** Authentication data and encrypted file metadata stored in **local SQLite**, separate from file system storage.  
- **Input Validation:** Prevents malicious uploads (e.g., blocks `.exe`, `.crx`, etc.).

---

## 📐 Usability & File Management

- 🧭 **User-Friendly Interface:** Designed for non-technical users (UAT score: 5/5 satisfaction).  
- 📘 **Built-In User Manual:** Searchable manual for features & best practices.  
- 🗂️ **Secure File Management:** Organized listings, secure deletion, Base64 export for encrypted files.

---

## 📸 Application Screenshots

### 1. Secure Account Registration  
Enforces strict password rules and uses masked input.  


---

### 2. File Management Dashboard  
Displays all encrypted files with upload & management options.  


---

### 3. Decryption Completion & Path  
Decrypted files saved to **Downloads/MyDecryptedFiles** for easy access.  


---

### 4. Searchable User Manual  
Allows quick lookup of file operations and security terms.  

---

## 💻 Technology Stack

| Component | Technology | Rationale |
|----------|------------|-----------|
| **Mobile Platform** | Android | Majority user preference |
| **Language** | Java | Strong support + Java Cryptography Architecture |
| **Database** | SQLite | Lightweight, secure, and serverless |
| **Development Method** | Agile | Fast iterations and continuous testing |
