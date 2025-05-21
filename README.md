# 🌌 PlanetsAR

**PlanetsAR** is an Augmented Reality application that allows users to explore detailed 3D models of planets in their real-world environment using their mobile device. The application leverages gyroscope functionality for intuitive interaction with the celestial models.

---

## 📱 Features

- **Interactive 3D Planet Models**: Accurately rendered planetary models with detailed textures  
- **Augmented Reality Visualization**: View planets in your real-world space through your device camera  
- **Gyroscope Controls**: Intuitive movement and rotation of planets based on device orientation  
- **Cross-Platform Compatibility**: Built for Android devices with ARCore support  

---

## 🛠️ Technology Stack

- **Engine**: Unity 6  
- **Rendering**: Universal Render Pipeline (URP)  
- **AR Framework**: AR Foundation  
- **Platform SDK**: ARCore for Android  
- **3D Rendering**: Custom-optimized 3D models with specialized materials  
- **Device Integration**: Gyroscope API for orientation-based controls  

---

## ⚙️ Setup and Installation

### Prerequisites

- Unity 6.0 or later  
- AR Foundation package  
- ARCore XR Plugin  
- Universal RP package  
- Android SDK 24+ (Android 7.0 Nougat or later)  
- Device with ARCore support and gyroscope  

### Installation

1. Clone this repository  
2. Open the project in Unity 6  
3. Ensure all required packages are imported:  
   - AR Foundation  
   - ARCore XR Plugin  
   - Universal RP  
4. Connect an ARCore-compatible Android device  
5. Build and run the application on your device  

---

## 🚀 Usage

1. Launch the application on your ARCore-compatible Android device  
2. Grant camera permissions when prompted  
3. Point your camera at a flat, well-lit surface  
4. The planet will appear in augmented reality  
5. Move your device to explore the planet from different angles  
6. Tilt your device to rotate the planet using gyroscope controls  

---

## 💻 Project Structure

PlanetsAR/
├── Assets/
│ ├── Scenes/
│ │ ├── HomeScreen.unity # Initial user interface
│ │ ├── Earth.unity # Main AR scene with Earth model
│ ├── Scripts/ # C# scripts for AR functionality
│ ├── Models/ # 3D planet models
│ ├── Materials/ # URP materials for planets
│ ├── Textures/ # Planet surface textures
│ ├── Settings/ # URP and AR configuration files
│ ├── XR/ # AR Foundation and ARCore settings


---

## 🔮 Future Development

- Add additional planets and celestial bodies  
- Implement planet information panels with scientific data  
- Add animation for planetary rotation  
- Enhance AR experience with surface plane detection  
- Optimize performance for wider device compatibility  
- Add social sharing functionality  
