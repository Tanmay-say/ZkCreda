# ZkCreda

A passwordless, decentralized identity system built with React Native and Expo.

## Features

- Biometric authentication (Face ID/Touch ID)
- Secure key pair generation and storage
- Challenge-response authentication
- Modern, clean UI

## Prerequisites

- Node.js (v14 or later)
- npm or yarn
- Expo CLI
- iOS Simulator (for iOS development)
- Android Studio (for Android development)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/zkcreda.git
cd zkcreda
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm start
# or
yarn start
```

4. Run on your preferred platform:
- Press `i` for iOS simulator
- Press `a` for Android emulator
- Scan the QR code with Expo Go app on your physical device

## Security Features

- Private keys are stored securely using the device's keystore
- Biometric authentication is required for all sensitive operations
- Challenge-response authentication prevents replay attacks
- No passwords or sensitive data are stored in plain text

## Development

The project uses:
- TypeScript for type safety
- React Navigation for routing
- Expo SecureStore for secure storage
- React Native Biometrics for biometric authentication
- Expo Local Authentication for device authentication

## License

MIT