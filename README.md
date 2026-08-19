# Lensora

Lensora is a Compose Multiplatform application designed to help contact lens wearers track their daily usage, manage prescriptions, and monitor their eye health.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/565305ee-be5f-4fa0-9050-0cfe79991c29">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/ab7b2c3d-9400-440e-9538-1b5a39ded8cd">
  <img width="1024" height="372" alt="Lensora Mockups" src="https://github.com/user-attachments/assets/16a276c5-74d7-40a0-ba8e-82a549990d30">
</picture>



## 🌟 Detailed Features

### ⏱️ Precision Wear Time Tracking
- **Live Interactive Timer**: Start, pause, resume, and stop a beautifully crafted, real-time counter to track your active lens wear time.
- **Daily Goals**: Set a target daily wear time to ensure you are not over-wearing your lenses and risking your eye health.

### 📝 Comprehensive Logging & Reporting
- **Manual Entry System**: Forget to hit start? Easily backdate and log wear sessions manually using the integrated date picker for any past day.
- **Detailed History & Analytics**: Navigate your entire wearing history in the Reports screen. Review your logs day-by-day to visualize your wearing habits and track consistency.

### 🏥 Medical & Prescription Management
- **Lens Details**: Safely store intricate details including your exact prescription for both eyes (OD/OS), brand name, lens type, and unique identification numbers.
- **Lifecycle Tracking**: Keep track of the exact date you received your current pair of lenses so you know when it's time to replace them.
- **Doctor Contacts**: Maintain your optometrist's or ophthalmologist's name, clinic availability, and set reminders for your next appointment.

### 🎨 Deep Aesthetic Customization
- **10+ Curated Color Themes**: Completely transform the app's look and feel with built-in palettes like *Glacier*, *Navy*, *Forest*, *Mint*, *Amethyst*, *Amber*, *Teal*, *Purple*, *Blue*, and *Rose*.
- **LiquidGlass Navigation**: Elevate your UI with an optional, visually stunning *LiquidGlass* frosted and translucent bottom navigation bar.
- **Typography & Clock Customization**: Tailor the main home screen timer's font, size, and specific color hex codes to perfectly match your personal aesthetic.
- **App Icons & Styling**: Personalize the app's primary background colors and report card styles to build your ideal environment.

## 🛠️ Tech Stack

- **Framework**: [Compose Multiplatform](https://www.jetbrains.com/lp/compose-multiplatform/)
- **Language**: Kotlin
- **Supported Platforms**: Android, Desktop (JVM)
- **Key Libraries**:
  - `kotlinx.datetime` for robust cross-platform date and time manipulation.
  - `multiplatform-settings` for persisting user preferences and app state.

## 🚀 Getting Started

### Prerequisites
- JDK 17
- Android Studio (Ladybug or later recommended) or IntelliJ IDEA

### Building and Running

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd Lens
   ```

2. **Run on Android**:
   Open the project in Android Studio, select the `composeApp` run configuration, and press **Run**.
   Alternatively, build via command line:
   ```bash
   ./gradlew :composeApp:installDebug
   ```

3. **Run on Desktop**:
   You can run the JVM desktop application using the following command:
   ```bash
   ./gradlew :composeApp:run
   ```

## 📂 Project Structure

- `composeApp/src/commonMain/`: Contains the core application logic, ViewModels (`LensViewModel`), screens, and UI components shared across platforms.
- `composeApp/src/androidMain/`: Android-specific implementations, including `MainActivity` and specific backdrop support.
- `composeApp/src/desktopMain/` *(if configured)*: Desktop JVM entry points.

## 📄 License
This project is provided as-is. Please see the `LICENSE` file for more details.
<img width="1024" height="372" alt="Lensora_Mockup_BlackText" src="https://github.com/user-attachments/assets/af9fd59b-c04b-4b17-bb15-a8834e1b8734" />
