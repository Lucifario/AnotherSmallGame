# AnotherSmallGame

## Overview
This is an **Augmented Reality (AR) game** built in Unity that allows players to **visualize planes**, **place objects**, and interact with them using **drag, rotate, and scale gestures**. The game uses AR Foundation to track the environment and enable immersive object placement.

## Requirements
Before running the game, ensure you have the following installed:

### **Software & SDKs:**
- **Unity** (Latest LTS recommended)
- **AR Foundation**
- **ARCore (Android)**
- **XR Plugin Management** enabled for your target platform

### **Device Requirements:**
- **Android:** ARCore-supported devices

## Installation & Setup
1. **Import the Unity Package:**
   - Open Unity and create a new 3D or AR project.
   - Go to **Assets > Import Package > Custom Package...**
   - Select the `.unitypackage` file and click **Import**.

2. **Enable XR Plugin Management:**
   - Go to **Edit > Project Settings > XR Plugin Management**.
   - Enable **ARCore (Android)** or **ARKit (iOS)** based on your platform.

3. **Build & Run:**
   - Connect your AR-supported device.
   - Set the platform to **iOS** or **Android** in **Build Settings**.
   - Click **Build & Run** to deploy the app.

## Known Issues
- Some objects may not align properly on uneven surfaces.
- Performance may vary depending on the device's AR capabilities.

## Future Improvements
- Add object snapping for better placement.
- Implement UI buttons for better interaction control.
- Introduce more object types with animations.

## License
This project is licensed under the **MIT License**.

---

For questions, issues, or feature requests, feel free to open an issue or contribute to the project! 🚀

