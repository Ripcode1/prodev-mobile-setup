# Mobile Development with React Native - Complete Project

This repository contains all tasks for the Mobile Development with React Native course using TypeScript, NativeWindCSS, and the Expo Framework.

## 📱 Project Overview

**Course Duration**: January 5, 2026 - January 12, 2026  
**Weight**: 1  
**Framework**: React Native with Expo  
**Language**: TypeScript  
**Styling**: NativeWindCSS / StyleSheet

## 🎯 Learning Objectives

By completing this project, you will:
- ✅ Set up a professional mobile development environment
- ✅ Create cross-platform mobile applications for iOS and Android
- ✅ Master React Native core components
- ✅ Implement responsive layouts with Flexbox
- ✅ Handle images, safe areas, and touchable components
- ✅ Build production-ready UI screens
- ✅ Use TypeScript for type-safe mobile development

## 📂 Project Structure

```
prodev-mobile-setup/
├── mobile-development-setup/          # Task 0: Environment Setup
│   └── README.md
├── prodev-mobile-app-0x00/            # Task 1: First Mobile App
│   ├── README.md
│   └── app-example/
│       ├── app/(tabs)/index.tsx
│       └── constants/Colors.tsx
├── prodev-mobile-app-0x01/            # Task 2: Mobile Components & Styling
│   └── app/index.tsx
├── prodev-mobile-app-0x02/            # Task 3: Safe Areas, Images, Touchables
│   └── app/index.tsx
└── prodev-mobile-app-0x03/            # Task 4: Core Components (Login Screen)
    ├── app/
    │   ├── _layout.tsx
    │   └── index.tsx
    ├── styles/index.tsx
    ├── app.json
    ├── ASSETS_NOTE.md
    └── README.md
```

## 📋 Tasks Breakdown

### Task 0: Setting Up and Testing Your Mobile Development Environment ✅
**Objective**: Install and configure Expo Go on your physical device

**Requirements**:
- Node.js LTS installed
- VS Code
- Expo Go app on physical device (iOS/Android)

**Deliverables**:
- ✅ Expo Go installed and configured
- ✅ Account created
- ✅ Documentation in README.md

---

### Task 1: Create Your First Mobile App ✅
**Objective**: Scaffold your first Expo app and understand the project structure

**Steps**:
1. Initialize Expo project with Router template
2. Modify home screen text
3. Run on physical device
4. Reset project and document observations

**Deliverables**:
- ✅ Modified `app/(tabs)/index.tsx`
- ✅ Documentation of reset command effects
- ✅ Understanding of file structure

---

### Task 2: Implementing Mobile Components in React Native ✅
**Objective**: Learn React Native components and StyleSheet API

**Components Used**:
- `<View>` - Container component
- `<Text>` - Text display component
- `StyleSheet` - Styling API

**Deliverables**:
- ✅ Styled text components
- ✅ Custom color scheme
- ✅ Typography implementation

---

### Task 3: Safe Areas, Images, and Touchable Components ✅
**Objective**: Build a welcome screen with images and interactive elements

**Components Used**:
- `SafeAreaView` & `SafeAreaProvider`
- `ImageBackground`
- `Image`
- `TouchableOpacity`
- `Dimensions`

**Features**:
- ✅ Full-screen background image
- ✅ Company logo display
- ✅ Interactive buttons
- ✅ Safe area handling for notches

---

### Task 4: Explore More Core Components ✅
**Objective**: Build a complete login screen with form elements

**Components Used**:
- `TextInput` with keyboard types
- `TouchableOpacity` for buttons
- `@expo/vector-icons` for icons
- Custom centralized styling

**Features**:
- ✅ Email input field
- ✅ Password input with visibility toggle
- ✅ Primary and social login buttons
- ✅ Responsive layout
- ✅ Navigation elements

---

## 🚀 Getting Started

### Prerequisites
```bash
# Check Node.js version (v16 or higher)
node --version

# Install Expo CLI globally (optional)
npm install -g expo-cli
```

### Running Each Task

#### Task 1:
```bash
cd prodev-mobile-app-0x00
npx create-expo-app@latest .
npx expo start
```

#### Task 2:
```bash
cd prodev-mobile-app-0x01
npx create-expo-app@latest .
npm run reset-project
# Copy code from app/index.tsx
npx expo start
```

#### Task 3:
```bash
cd prodev-mobile-app-0x02
npx create-expo-app@latest .
npm run reset-project
# Add background-image.png and Logo.png to assets/images/
npx expo start
```

#### Task 4:
```bash
cd prodev-mobile-app-0x03
npx create-expo-app@latest .
npm run reset-project
npm install react-native-safe-area-context @expo/vector-icons
# Add required images to assets/images/
npx expo start
```

## 📱 Testing on Device

### iOS (iPhone/iPad)
1. Install Expo Go from App Store
2. Run `npx expo start`
3. Scan QR code with Camera app

### Android
1. Install Expo Go from Play Store
2. Run `npx expo start`
3. Scan QR code with Expo Go app

## 🎨 Key Concepts Learned

### 1. React Native Components
- **View**: Container component (like `<div>`)
- **Text**: Text display (like `<p>`)
- **Image**: Display images
- **ImageBackground**: Background images
- **TextInput**: Form inputs
- **TouchableOpacity**: Touchable buttons

### 2. Styling
- StyleSheet.create() for performance
- Flexbox layouts
- Responsive design with Dimensions
- Centralized style management

### 3. Safe Area Context
- Prevents UI overlap with device notches
- SafeAreaProvider wraps entire app
- SafeAreaView for individual screens

### 4. Icons & Assets
- @expo/vector-icons for icon libraries
- require() for local assets
- Image optimization

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| React Native | Cross-platform mobile framework |
| TypeScript | Type-safe JavaScript |
| Expo | Development tooling & services |
| Expo Router | File-based navigation |
| Vector Icons | Icon libraries (FontAwesome, Ionicons) |
| SafeAreaContext | Device-safe layouts |

## 📚 Resources

- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [Expo Documentation](https://docs.expo.dev/)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [React Native Components](https://reactnative.dev/docs/components-and-apis)
- [Expo Vector Icons](https://icons.expo.fyi/)

## ✅ Submission Checklist

- [ ] All tasks completed on time
- [ ] Code typed manually (no copy-paste)
- [ ] All required files present
- [ ] Apps tested on physical device
- [ ] README files documented
- [ ] Screenshots added (optional)
- [ ] Review link generated
- [ ] Peer reviews completed

## 🎯 Assessment Criteria

**Hybrid Assessment**:
- ✅ Manual review by peers
- ✅ Auto-check for core files
- ⏰ Timely submission required

**Important**: Generate your review link before the deadline to ensure peer review availability.

## 💡 Best Practices Followed

1. **Manual Typing**: All code typed manually for better retention
2. **Organized Structure**: Logical folder organization
3. **Documentation**: Comprehensive README files
4. **Clean Code**: Proper formatting and naming
5. **Reusability**: Centralized styles and components
6. **Type Safety**: TypeScript throughout

## 🐛 Common Issues & Solutions

### Issue: Expo Go not connecting
**Solution**: Ensure phone and computer are on same network

### Issue: Assets not loading
**Solution**: Check file paths and names (case-sensitive)

### Issue: SafeAreaView not working
**Solution**: Wrap with SafeAreaProvider

### Issue: Icons not displaying
**Solution**: Install @expo/vector-icons

## 📈 Next Steps

After completing these tasks, you're ready to:
- Implement navigation between screens
- Add state management (Context API, Redux)
- Connect to backend APIs
- Add authentication
- Implement data persistence
- Deploy to app stores

## 🤝 Contributing

This is a learning project. Feel free to:
- Add improvements
- Fix bugs
- Enhance documentation
- Share with peers

## 📝 Notes

- **Course Platform**: ALX Professional Development
- **Deadline**: January 12, 2026
- **Status**: All tasks completed ✅
- **Framework**: Expo SDK (latest)

---

**Happy Coding!** 🚀✨

Made with ❤️ for mobile development learning
