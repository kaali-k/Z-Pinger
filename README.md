# Z Pinger – Connection Keeper 📶

**Z Pinger** is a lightweight Android utility designed to keep your internet connection alive by preventing the network interface from entering idle or dormant mode. It's especially useful for users on unstable ISPs or specific networks (like Hutch in Sri Lanka) where connection timeouts are common.

---

## 🌟 Key Features

- **🚀 Background Keep-Alive**: Runs as a persistent foreground service, maintaining the connection even while your phone is locked or you're using other apps.
- **⚙️ Custom Ping Intervals**: Choose from preset intervals (5s, 10s, 30s, etc.) to balance stability and data consumption.
- **🖥️ Live Log Console**: Real-time visualization of connection status and ping responses.
- **🔗 Profile Support**: Save up to 3 custom ping target URLs for different networking scenarios.
- **🛡️ Data Efficient**: Uses thin HTTP HEAD requests to minimize data overhead while achieving maximum stability.

---

## 🛠️ Technology Stack

- **Framework**: [Flutter](https://flutter.dev/)
- **Language**: Dart
- **Libraries**: `dio`, `flutter_background_service`, `flutter_local_notifications`
- **Branding**: Zentix Official

---

## 📲 Installation

1. Download the latest APK from the [Releases](https://github.com/kaali-k/kalanasahan-portfolio/releases/) page.
2. Open the `.apk` file and tap **Install**.
3. Grant necessary permissions (Internet & Notification).
4. Enter a target URL (e.g., `google.com`) and tap **Start**.

---

## 🔒 Privacy

Z Pinger is **Offline-First**. No personal data is collected or transmitted. It only pings your specified targets to maintain network activity.

---

## 👨‍💻 Developed by
**Kalana Sahan Dillimuni**  
*A Zentix Production*

[Zentix Official](https://kalanasahan.com/zentix.html)
