# 📸 Custom Camera Vitals Screen

A premium, high-performance Android application that leverages the **SmartSpectra SDK** to measure and visualize real-time physiological vitals using just a smartphone camera.

![Vitals Demo](SmartSpectra/android/media/android-quickstart.gif)

---

## 🌟 The Magic: How it Works?

This application turns your smartphone into a medical-grade sensor using a technology called **rPPG (remote Photoplethysmography)**.

1.  **Detection**: Every heart beat pumps blood into your facial vessels, causing microscopic color changes in your skin.
2.  **Capture**: The camera sensor detects these subtle light fluctuations, which are invisible to the human eye.
3.  **Processing**: The **SmartSpectra SDK** processes these signals using advanced AI and signal processing algorithms.
4.  **Result**: The app extracts clinical-grade metrics like heart rate, breathing rate, and stress levels (HRV) in real-time.

---

## 🚀 Key Features

- **Real-time Vitals Tracking**:
  - 💓 **Pulse Rate**: Live heart rate in BPM.
  - 🫁 **Breathing Rate**: Respiratory rate tracking.
  - 📉 **HRV RMSSD**: Heart Rate Variability for stress and recovery analysis.
  - 🎭 **Expression Analysis**: Real-time facial expression classification (Happy, Neutral, Sad, etc.).
- **Dynamic Waveform Visualization**:
  - **Arterial Pressure**: Live plethysmograph waveform.
  - **Chest & Abdomen Breathing**: Synchronized respiratory waveforms.
- **Premium UI/UX**:
  - Dark-themed, glassmorphic design.
  - High-performance programmatic layouts (Zero XML overhead).
  - Live camera preview overlay with real-time status pills.

---

## 🛠 Tech Stack

- **Platform**: Android (Kotlin)
- **SDK**: [SmartSpectra SDK v3.0.0](https://physiology.presagetech.com)
- **Camera Engine**: Android CameraX
- **Architecture**: Clean Architecture with Lifecycle-aware components.

---

## 📦 Project Structure

```text
.
├── CoolVitals/            # Core Android Application source
│   ├── app/               # Main application module (Kotlin logic & UI)
│   └── build.gradle.kts   # Gradle dependencies & config
├── SmartSpectra/          # SmartSpectra SDK Documentation & Samples
└── README.md              # Project documentation (You are here)
```

---

## 🚀 Getting Started

### Prerequisites

- Android Studio (Iguana or newer recommended)
- Physical Android device (API 28+)
- A valid **SmartSpectra API Key**

### Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/abhivardhan20-coder/Custom-Camera-Vitals-Screen.git
   ```

2. **Set your API Key**:
   Open `CoolVitals/app/src/main/java/com/example/coolvitals/MainActivity.kt` and replace the placeholder:
   ```kotlin
   const val API_KEY = "YOUR_API_KEY"
   ```

3. **Build and Run**:
   - Open the `CoolVitals` folder in Android Studio.
   - Sync Gradle and run on your physical device.

---

## 🤝 Support & License

- **License**: MIT License.
- **SDK Support**: For technical issues regarding the SmartSpectra SDK, contact [support@presagetech.com](mailto:support@presagetech.com).

---

Developed with ❤️ using **SmartSpectra SDK**.
