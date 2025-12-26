# Current Activity - Professional Developer Tool


A powerful and professional Android developer tool that displays real-time information about the current foreground app's package name and activity in a customizable floating window.

## ✨ Features

### Core Features
- 🎯 **Real-time Activity Detection** - Instantly detects and displays current app activities
- 🪟 **Floating Window** - Always-on-top draggable window with professional UI
- 📋 **One-Tap Copy** - Copy package names and activities to clipboard
- 📊 **Activity History** - Track and review previously opened activities
- ⚙️ **Customizable Settings** - Adjust opacity, size, and behavior

### Advanced Features
- 🎨 **Material Design 3** - Modern, beautiful UI with dynamic theming
- 📌 **Pin Window** - Lock window position when needed
- 🔽 **Minimize Mode** - Collapse window to save screen space
- 🔔 **Vibration Feedback** - Haptic feedback on interactions
- 🚀 **Auto Start** - Optional boot-on-startup
- 📱 **Adaptive UI** - Works on all screen sizes and orientations

## 📱 Screenshots

| Screen 1 | Screen 2 | Screen 3 | Screen 4 | Screen 5 |
| :---: | :---: | :---: | :---: | :---: |
| ![1](Screenshots/screenshot_1.png) | ![2](Screenshots/screenshot_2.png) | ![3](Screenshots/screenshot_3.png) | ![4](Screenshots/screenshot_4.png) | ![5](Screenshots/screenshot_5.png) |

## 🔧 Technical Specifications

- **Package Name**: `com.akcreation.currentactivity`
- **Min SDK**: 21 (Android 5.0 Lollipop)
- **Target SDK**: 36 (Android 15)
- **Java Version**: 17
- **Architecture**: Service-based with Accessibility API
- **Design**: Material Design 3

## 📋 Permissions Required

### Mandatory Permissions
1. **Display Over Other Apps** (`SYSTEM_ALERT_WINDOW`)
   - Required for floating window functionality
   
2. **Accessibility Service** (`BIND_ACCESSIBILITY_SERVICE`)
   - Required to detect current foreground activities
   
### Optional Permissions
3. **Notifications** (`POST_NOTIFICATIONS`) - Android 13+
   - For foreground service notifications

### Method 2: Download APK
Download the latest APK from the [Releases](https://github.com/AKCREATIONDEV/CurrentActivity/releases) page.

## 📖 Usage

1. **Grant Permissions**
   - Enable "Display over other apps" permission
   - Enable "Accessibility Service" for Current Activity
   - (Optional) Allow notifications

2. **Enable Floating Window**
   - Toggle the switch on main screen
   - The floating window will appear

3. **Interact with Window**
   - **Drag**: Move window anywhere on screen
   - **Tap package/activity**: Copy to clipboard
   - **Copy button**: Copy all information
   - **Pin button**: Lock window position
   - **Minimize button**: Collapse window
   - **Close button**: Stop service

## 🎨 Customization

### Window Appearance
- **Opacity**: 50% - 100%
- **Size**: Small, Medium, Large
- **Position**: Draggable anywhere

### Behavior Settings
- **Vibration Feedback**: ON/OFF
- **Save History**: ON/OFF
- **Auto Start**: ON/OFF

## 🔐 Privacy

This app:
- ✅ Does NOT collect any personal data
- ✅ Does NOT send data to any server
- ✅ Works completely offline
- ✅ Only stores activity history locally
- ✅ All data stays on your device

The Accessibility Service is used ONLY to detect the current foreground app and activity. No other data is accessed or stored.

## 📝 To-Do

- [ ] Export history to CSV/JSON
- [ ] Add search functionality in history
- [ ] Widget support
- [ ] Quick settings tile
- [ ] Multiple window themes
- [ ] App icon customization
- [ ] Floating window animations

## 🐛 Bug Reports

Found a bug? Please open an [issue](https://github.com/AKCREATIONDEV/CurrentActivity/issues) with:
- Device model and Android version
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

## 📄 License

```
MIT License

Copyright (c) 2024 AK Creation

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👨‍💻 Developer

**AK_CREATION_DEV**

- GitHub: [AK_CREATION_DEV](https://github.com/AKCREATIONDEV)
- Telegram: [AK_CREATION_DEV](t.me/AK_CREATION_DEV)

## 🙏 Acknowledgments

- Material Design 3 by Google
- Android Accessibility API

---

<div align="center">
Made with ❤️ by AK_CREATION_DEV
</div>