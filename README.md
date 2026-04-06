# Geo-Tracking-Navigation-app
A mobile app that is powered by Java and Android studio, that can store geographical locations and access google maps to navigate to a saved location.

## 📁 Project Structure & Code Guide

This repository contains the full source code for the **Geo Tracking & Navigation App**, built using **Java** and **Android Studio**.  
To help developers quickly understand and navigate the project, the structure is outlined below.

---

### 📦 Root Directory Overview
Geo_Tracking_App/ │ ├── app/                     # Main Android application module │   ├── src/ │   │   ├── main/ │   │   │   ├── java/        # All Java source code (Activities, Services, Helpers) │   │   │   ├── res/         # Layouts, drawables, values, UI resources │   │   │   └── AndroidManifest.xml │   │   └── test/            # Unit tests │   │ │   ├── build.gradle         # Module-level Gradle config │   └── proguard-rules.pro   # ProGuard configuration │ ├── gradle/                  # Gradle wrapper files ├── build.gradle             # Project-level Gradle config ├── settings.gradle          # Module linking └── README.md                # Project documentation


---

### 🧭 Where the Main Code Lives

#### **1. Java Source Code**
All core logic is inside: **app/src/main/java/**

This includes:
- Activity classes  
- Location tracking logic  
- Google Maps integration  
- Database/storage handlers  
- Utility/helper classes  

#### **2. UI Layouts**
All XML UI files are located in: **app/src/main/res/layout/**


#### **3. App Resources**
Icons, colors, strings, and themes are inside: **app/src/main/res/**


#### **4. App Manifest**
Defines permissions (e.g., location, internet), activities, and services: **app/src/main/AndroidManifest.xml**


---

### 🗺️ Key Features & Code Locations

| Feature | Code Location |
|--------|----------------|
| Save geographical locations | `java/.../LocationSaveActivity.java` |
| View saved locations | `java/.../LocationListActivity.java` |
| Navigate using Google Maps | `java/.../NavigationActivity.java` |
| Database / Storage | `java/.../database/` |
| Map rendering | `java/.../maps/` |
| Permissions handling | `java/.../utils/PermissionsHelper.java` |

---

### 🚀 Getting Started (For Developers)

1. Clone the repository  
   ```bash
   git clone https://github.com/Albayne/Geo-Tracking-Navigation-app.git

   - Open the project in Android Studio
2. - Sync Gradle
3. - Run the app on an emulator or physical device

