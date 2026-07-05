# 📷 QR Code Scanner (Desktop Edition)

A fast, interactive web-based QR code scanner optimized specifically for PC and desktop environments. It uses your computer's webcam to detect and decode QR codes in real-time, offering a clean UI and instant actions for detected links.

## 🌐 Live Demo

Check out the live version of the project here:  
👉 [**Open QR Code Detector**](https://afnan-nex.github.io/qr-code-detector/qr.html)

## ✨ Features

- **Real-Time Scanning**: Instantly detects and decodes QR codes using your desktop webcam.
- **Desktop Optimized**: Tailored specifically for PC and laptop screens, ensuring a smooth, focused, and distraction-free user experience.
- **Multi-Webcam Support**: If you have multiple cameras connected to your PC (e.g., built-in laptop camera and an external USB webcam), easily toggle between them using the 🔄 Switch button.
- **Instant Actions**: When a QR code is detected, you can directly **Open** the link in a new tab, **Copy** it to your clipboard, or **Cancel**.
- **Robust Error Handling**: Clear UI prompts for camera initialization, with a **Retry** button if access is denied or if the webcam is blocked by another application.

## 🚀 How to Use

1. Open the [Live Demo](https://afnan-nex.github.io/qr-code-detector/qr.html) in a modern desktop web browser (Chrome, Edge, Firefox, etc.).
2. Allow **Camera Access** when prompted by your browser. *(Note: Ensure no other applications like Zoom or Skype are currently using your webcam).*
3. Hold a QR code up to your webcam or place it in front of your laptop camera.
4. Once detected, the content will be displayed on screen. Choose to **Open** the link, **Copy Link**, or **Cancel**.

## 🛠️ Technologies Used

- **HTML5 / CSS3**: For the structure and styling of the desktop-optimized UI.
- **JavaScript**: For the core scanning logic, state management, and DOM manipulation.
- **WebRTC / MediaDevices API**: For accessing and managing the desktop webcam stream.
- **QR Decoding Library**: For processing video frames and extracting QR code data.

## 👤 Author

Created with ❤️ by **AFNAN**

---

<div align="center">
  <i>If you like this project, consider giving it a ⭐ on GitHub!</i>
</div>
