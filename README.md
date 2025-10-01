# Test Android Endor Scan

A simple React Native Hello World app to test the Endor SCA scan workflow.

## Project Structure

```
├── .github/workflows/endor-sca-scan.yml  # GitHub Actions workflow
├── apps/mobile/                          # React Native app
│   ├── android/                          # Android configuration
│   ├── ios/                              # iOS configuration
│   ├── App.tsx                           # Main app component
│   └── package.json                      # App dependencies
└── package.json                          # Root workspace configuration
```

## Features

- Simple Hello World React Native app
- Configured for Android and iOS builds
- pnpm workspace setup
- GitHub Actions workflow for Endor SCA scanning

## Usage

This project is designed to test the Endor SCA scan workflow. The app itself is minimal and displays a simple "Hello World" message.

## Workflow

The GitHub Actions workflow will:
1. Set up Node.js, Java, and Android SDK
2. Install dependencies using pnpm
3. Build the React Native app
4. Run Endor Labs SCA scan

## Development

To run locally:

```bash
# Install dependencies
pnpm install

# Navigate to mobile app
cd apps/mobile

# Install app dependencies
pnpm install

# Run on Android
pnpm run android

# Run on iOS
pnpm run ios
```
