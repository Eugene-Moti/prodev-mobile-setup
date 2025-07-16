# React Native Components and Styling

## Objective
Implement React Native components and styling with Expo and TypeScript.

## Steps Followed

1. **Created new Expo project**
mkdir prodev-mobile-app-0x01
cd prodev-mobile-app-0x01
npx create-expo-app@latest . --template tabs

2. **Reset project**
- Removed default template:
  ```
  rm -rf app
  ```
- Created new `app/index.tsx`

3. **Added entry screen code**
- Displayed "Entry Screen - Awesome" with 3 styled `<Text>` components.

4. **Defined styles**
- Used `StyleSheet.create` for:
  - container
  - largeText
  - mediumText
  - smallText

5. **Ran app**
npx expo start
- Verified display in emulator and Expo Go.

## File Structure
.
├── app/
│ └── index.tsx
├── assets/
├── package.json
├── ...


## Observations
- Styling works as expected.
- Expo reloads changes automatically.
- Using `StyleSheet` keeps styles organized.

