# Janus

**A React Native mobile app for managing properties, their buildings, and the visits made to them.**

The mobile client of a property management system: list properties and buildings, and register visits such as maintenance, cleaning, and inspections along with their purpose.

[![React Native](https://img.shields.io/badge/React_Native-0.70-20232A?logo=react)](https://reactnative.dev/) [![Expo](https://img.shields.io/badge/Expo-000020?logo=expo)](https://expo.dev/) [![Axios](https://img.shields.io/badge/Axios-5A29E4?logo=axios)](https://axios-http.com/)

---

## 📖 Overview

Janus is built for managing properties that contain multiple buildings. Each building sees regular activity (maintenance, cleaning, visits), and the app records each visit and why it happened, so there is a clear log of what was done and when.

---

## ✨ Core Features

- 🏢 **Properties & Buildings**: List properties and the buildings inside them
- 📝 **Visit Registration**: Record visits and their purpose (maintenance, cleaning, visiting)
- 📷 **QR Codes**: Scan and generate QR codes to identify buildings quickly
- 🗺️ **In-App Maps**: Map view and geolocation for locating buildings
- 📤 **Media & Sharing**: Camera access, media library, and sharing support

---

## 🏗️ Architecture

A standard Expo project layout. The app communicates with a backend over HTTP using Axios.

```
janus-app/
├─ assets/       → Images and static assets
├─ components/   → Reusable UI components
├─ src/theme/    → Theme and styling
├─ App.js        → Application entry point
├─ app.json      → Expo configuration
└─ eas.json      → EAS build configuration
```

---

## 🛠️ Tech Stack

| Layer            | Technology                                                  |
| ---------------- | ----------------------------------------------------------- |
| Framework        | React Native                                                |
| Tooling          | Expo, EAS (builds), expo-updates                            |
| Navigation       | React Navigation (stack), Gesture Handler, Reanimated       |
| Maps & Location  | react-native-maps, expo-location                            |
| QR & Camera      | expo-barcode-scanner, expo-camera, react-native-qrcode-svg  |
| Networking       | Axios                                                       |
| Media & Sharing  | expo-media-library, expo-sharing                            |
| Utilities        | Moment.js, react-native-vector-icons                        |

---

## 📌 Project Status

Janus is the mobile client for a property management system, built with React Native and Expo.

---

Built by **Jonathan Adel**