# 🚀 Launcher Optimizer

Native Android application built with **Kotlin** and designed following **Material Design 3** guidelines, created to boost performance, smoothness, and memory management for system launchers.

---

## ✨ Key Features

* **🔍 Automatic Detection:** Scans the device to identify all installed launchers.
* **⚡ Optimization Profiles:** Three customizable adjustment levels to fit your needs:
  * **Soft:** Light tweaks without compromising visual effects.
  * **Balanced:** Ideal balance between smoothness and aesthetics.
  * **Aggressive:** Maximum performance and resource freeing.
* **🧹 Cache & Memory Management:** Tools to clear or compress the launcher cache and prioritize background execution.
* **🎨 Visual & Sound Customization:** 
  * System animation scale reduction.
  * Support for *Material Expressive* animations and dynamic theming (*Material You*).
  * Interactive touch sound effects.
* **🤖 Automation:** Option to automatically run optimization upon opening the app and receive status notifications.

---

## 🔐 Required Permissions

To apply real performance and interface improvements to the system, the application requests the following permissions:

| Permission | Purpose |
| :--- | :--- |
| `WRITE_SETTINGS` | Modify system animation speeds and system settings. |
| `SYSTEM_ALERT_WINDOW` | Display overlays and adjust UI elements on top of other apps. |
| `REQUEST_IGNORE_BATTERY_OPTIMIZATIONS` | Prevent Android from stopping or restricting the background process. |
| `POST_NOTIFICATIONS` | Send alerts when an optimization process is completed. |

---

## 🛠️ Tech Stack

* **Language:** [Kotlin](https://kotlinlang.org)
* **Concurrency:** Kotlin Coroutines
* **User Interface:** XML + [Material Components for Android](https://github.com) (Material 3)
* **Architecture & Components:** AndroidX (AppCompat, Core KTX, Lifecycle, ConstraintLayout)

---

## 📥 Installation

1. Go to the [**Releases**](../../releases) section of this repository.
2. Download the `.apk` file from the latest available release (`v1.1.1`).
3. Open it on your Android device and enable installation from **Unknown Sources** if prompted by the system.
4. Grant the required permissions inside the app to start optimizing.

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
