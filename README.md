# Andorid-Studio-FastFood-App-in-Java

# 🍔 Fast Food Management System – Android App

A beginner-level **Fast Food Management System** developed in **Android Studio using Java**.

The application provides separate user and admin functionality for managing food items, orders, users, feedback, and deliveries.

## 📱 Project Information

- **Project Type:** Android Application
- **Programming Language:** Java
- **IDE:** Android Studio
- **Build System:** Gradle
- **Database:** MySQL / Project Database
- **Level:** Beginner
- **Platform:** Android

## ✨ Features

### 👤 User Side
- User registration
- User login
- Home screen
- View food menu
- Add food items to cart
- Place orders
- View orders
- User profile
- Submit feedback

### 🔐 Admin Side
- Admin login
- Admin dashboard
- Manage users
- Manage menu items
- Manage food items
- Manage deliveries
- View feedback

## 📂 Project Structure

```text
FastFood-App/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   └── res/
│   │   └── test/
│   └── build.gradle.kts
│
├── gradle/
│   └── wrapper/
│
├── build.gradle.kts
├── gradle.properties
├── settings.gradle.kts
├── gradlew
├── gradlew.bat
├── .gitignore
└── README.md
```

## ⚙️ How to Download and Run the Project

### 1. Clone the Repository

Open Git Bash or PowerShell:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Then enter the project directory:

```bash
cd YOUR_PROJECT_FOLDER
```

### 2. Open the Project in Android Studio

1. Open **Android Studio**.
2. Select **Open**.
3. Select the cloned project folder.
4. Wait for Android Studio to load the project.

Android Studio should detect the Gradle project automatically.

## 📦 Gradle Setup

**You do NOT need to install the exact Gradle version manually.**

This project uses the **Gradle Wrapper**.

The repository contains:

```text
gradlew
gradlew.bat
gradle/wrapper/
```

The Gradle Wrapper allows the project to download and use the required Gradle version automatically.

### Windows

From the project folder, run:

```powershell
.\gradlew.bat build
```

or:

```powershell
.\gradlew.bat assembleDebug
```

### Linux / macOS

Run:

```bash
./gradlew build
```

If necessary, make the wrapper executable:

```bash
chmod +x gradlew
```

Then:

```bash
./gradlew build
```

## 🔄 Gradle Sync in Android Studio

After opening the project:

1. Open the project in Android Studio.
2. Wait for Gradle synchronization.
3. If Android Studio displays **Sync Project with Gradle Files**, click it.
4. Allow Android Studio to download required Gradle dependencies.
5. Wait until synchronization finishes.

You normally do **not** need to download Gradle separately.

## 🛠️ Requirements

Install the following on the new computer:

- Android Studio
- Android SDK
- Android SDK Platform required by the project
- JDK version compatible with the Android Gradle Plugin

The project itself provides the Gradle Wrapper.

## ⚠️ Important: `local.properties`

Do **not** upload `local.properties` to GitHub.

`local.properties` contains the Android SDK location specific to your computer. For example, your uploaded file contains a Windows-specific SDK path:

```text
sdk.dir=C:\Users\sabes\AppData\Local\Android\Sdk
```

This path will be different on another computer.

Therefore, `local.properties` is intentionally excluded from Git using `.gitignore`.

### On another computer

Android Studio normally creates `local.properties` automatically when the project is opened and the Android SDK is configured.

If it does not, create it in the project root and set your local SDK path.

Example Windows:

```properties
sdk.dir=C:\\Users\\YOUR_USERNAME\\AppData\\Local\\Android\\Sdk
```

Do **not** copy the SDK path from another computer.

## 🚫 Files That Should Not Be Uploaded

The following local/generated files should normally remain outside Git:

```text
.gradle/
build/
app/build/
local.properties
.idea/workspace.xml
.idea/caches/
```

The project's `.gitignore` already excludes several of these files.

## 🔑 Configuration

Before running the application on another computer, check whether the project requires:

- Database configuration
- API URLs
- Firebase configuration
- Server configuration
- Android SDK configuration

Do not commit private passwords, API secrets, database credentials, or private keys to GitHub.

## 🧹 If Gradle Sync Fails

Try the following:

### Option 1 — Sync Project

In Android Studio:

```text
File → Sync Project with Gradle Files
```

### Option 2 — Clean and Build

Windows:

```powershell
.\gradlew.bat clean
.\gradlew.bat build
```

Linux/macOS:

```bash
./gradlew clean
./gradlew build
```

### Option 3 — Check SDK

Open:

```text
Android Studio
→ Settings
→ Languages & Frameworks
→ Android SDK
```

Make sure the required Android SDK is installed.


## 👨‍💻 Developer

**Sabestean**

Beginner Android Studio project developed for learning and practicing Java, Android development, Gradle, database integration, and application management.

## 📄 License

This project is intended for educational and learning purposes.
