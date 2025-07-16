# First Mobile App – Expo Router Setup

## Objective
Set up an Expo Router mobile application, modify the Home Screen, and understand the project structure.

## Steps Followed

1. **Created project directory**
mkdir prodev-mobile-app-0x00
cd prodev-mobile-app-0x00

2. **Initialized Expo project with Router template**
npx create-expo-app@latest . --template tabs

3. **Modified Home Screen**
- Edited `app/(tabs)/index.tsx`
- Replaced default text with:
  ```
  ** First App Created **
  ```
4. **Started development server**
npx expo start

- Scanned QR code with Expo Go.
- Verified the app displays the new text.

5. **Reset application**
npm run reset-project

- Observed cache cleared and app reloaded.

## Observations from `reset-project`
- The app rebuilds from a clean state.
- Changes remain intact.
- Cache is purged, ensuring no stale assets.

## Project Structure

├── app/
│ └── (tabs)/
│ └── index.tsx
├── assets/
├── node_modules/
├── package.json
├── app.json
├── tsconfig.json
└── ...
