# Create React Native app with expo

## 1. Install Expo CLI

```sh
npm install -g expo-cli
```

## 2. Create a New Expo Project

```sh
npx create-expo-app app_name
```

## 3. Install Dependencies

```sh
npx expo install <package-name>

```

## 4. Start the Development Server

```sh
npx expo start
```

## 5. Local Dev Build (Android)

```sh
npx expo prebuild -p android
npx expo run:android
```

## 6. Build Standalone App (EAS Build)

```sh
npm install -g eas-cli
npx eas login
npx eas build:configure
npx eas build
```
