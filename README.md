# Site Search App (Capacitor)

A simple mobile web app wrapped with Capacitor to search for site names and display results with Google Maps links.

## Features

- Search site by exact name
- Show nearby sites within a selected radius
- Google Maps integration
- Mobile friendly UI
- Sideload-ready for Android and iOS

## Setup Instructions

1. Clone this repo
2. Run `npm install`
3. Add platforms:
    ```bash
    npx cap add android
    npx cap add ios
    ```
4. Run it:
    ```bash
    npx cap open android
    ```

## Sideloading

- Use Android Studio to build APK
- Use Xcode to build IPA (macOS required)
