## Mobile Development Setup

### Setup
1. Visit the Official Expo Go homepage: https://expo.dev/go
2. Select the latest SDK Version
3. Click on install for your device.
  - Android: Install from the Google Play Store
  - IOS: Install from the App Store
4. Open the Expo Go app o your device
5. Create a new account or log in if you already have one

### Additional Setup Processes

6. Install Node.js and npm on your computer if not already installed.  
  - Download from [nodejs.org](https://nodejs.org/)
7. Install the Expo CLI globally by running:
  ```bash
  npm install -g expo-cli
  ```
8. Initialize a new Expo project:
  ```bash
  expo init my-new-project
  ```
9. Navigate to your project directory:
  ```bash
  cd my-new-project
  ```
10. Start the development server:
   ```bash
   expo start
   ```
11. Scan the QR code displayed in your terminal or browser using the Expo Go app on your device to preview your project.

### Common Challenges

- **Network Issues:** Ensure your computer and mobile device are on the same Wi-Fi network for Expo Go to connect.
- **Dependency Errors:** If you encounter errors during installation, try clearing npm cache or reinstalling dependencies.
- **Device Compatibility:** Some features may not work on all devices or require additional permissions.
- **Expo SDK Updates:** Keep your Expo CLI and Expo Go app updated to avoid compatibility issues.