# Task 1: Create Your First Mobile App

## Objective
Set up your first mobile application using the Expo Router template and document the scaffolding process.

---

## Steps Followed for Scaffolding

### Step 1: Navigate to Project Directory
```bash
cd prodev-mobile-setup
```

### Step 2: Initialize Expo Project
```bash
npx create-expo-app@latest .
```

**What happened:**
- Expo CLI created a new React Native project using the latest Expo Router template
- The project was initialized with TypeScript support
- A complete file structure was generated including:
  - `app/` directory for routes and screens
  - `assets/` directory for images and fonts
  - `constants/` directory for app-wide constants
  - Configuration files (`app.json`, `package.json`, `tsconfig.json`)

### Step 3: Modify the Home Screen
1. Opened `app/(tabs)/index.tsx`
2. Located the default text "Welcome!"
3. Changed it to "**First App Created**"

**Code modification:**
```typescript
// Before
<Text>Welcome!</Text>

// After
<Text>First App Created</Text>
```

### Step 4: Run and Test Application
```bash
npx expo start
```

**Testing process:**
- Started the Expo development server
- A QR code appeared in the terminal
- Scanned the QR code using:
  - **iOS**: Phone's Camera app
  - **Android**: Expo Go app
- The app successfully loaded on my physical device
- The home screen displayed "First App Created" as expected

---

## Observations from `reset-project` Command

### Running the Reset Command
```bash
npm run reset-project
```

### What Happened During Reset

When I ran the `npm run reset-project` command, the following changes occurred:

1. **Removed Example Code**
   - All boilerplate example screens were deleted
   - Template components and sample code were removed
   - The app was stripped down to a minimal starting point

2. **Cleaned Up Directory Structure**
   - The `app/(tabs)/` directory was simplified
   - Example tabs and navigation components were removed
   - Only essential files remained

3. **Asset Cleanup**
   - Example images and icons in `assets/` folder were removed
   - Default splash screens and placeholders were cleared
   - Font files from the template were deleted

4. **Files That Remained**
   - Core configuration files (`app.json`, `package.json`, `tsconfig.json`)
   - Basic app structure
   - Root layout files
   - Essential dependencies in `package.json`

5. **Script Execution**
   - The script `scripts/reset-project.js` was executed
   - It performed a cleanup operation on the project
   - After completion, I had a clean slate to build my custom app

### Why Reset is Useful

The `reset-project` command is valuable because:
- **Clean Starting Point**: Removes all template code you don't need
- **Faster Development**: No need to manually delete example files
- **Better Understanding**: Forces you to build from scratch, improving learning
- **Cleaner Git History**: Start with only the code you write
- **No Template Clutter**: Avoids confusion from unused example components

### Project State After Reset

After running the reset command:
- ✅ Configuration files intact
- ✅ Dependencies still installed
- ✅ Basic app structure preserved
- ✅ No example code or components
- ✅ Ready for custom development from scratch

---

## File Structure Understanding

After scaffolding, the project structure looks like this:

```
prodev-mobile-app-0x00/
├── app/
│   ├── (tabs)/
│   │   ├── index.tsx          # Home screen (modified)
│   │   ├── explore.tsx         # Second tab
│   │   └── _layout.tsx         # Tab navigation config
│   ├── _layout.tsx             # Root layout
│   └── +not-found.tsx          # 404 page
├── assets/
│   ├── images/                 # App images
│   └── fonts/                  # Custom fonts
├── constants/
│   └── Colors.tsx              # Color definitions
├── components/                 # Reusable components
├── hooks/                      # Custom React hooks
├── scripts/
│   └── reset-project.js        # Reset script
├── app.json                    # Expo configuration
├── package.json                # Dependencies
├── tsconfig.json               # TypeScript config
└── README.md                   # This file
```

---

## Key Learnings

1. **Expo Router**: Uses file-based routing (similar to Next.js)
2. **TypeScript**: Built-in TypeScript support for type safety
3. **Tab Navigation**: The `(tabs)` folder creates tab-based navigation
4. **Hot Reload**: Changes appear instantly on the device
5. **Cross-Platform**: Single codebase works on iOS and Android

---

## Technologies Used

- **React Native**: Cross-platform mobile framework
- **TypeScript**: Type-safe JavaScript
- **Expo**: Development platform and tooling
- **Expo Router**: File-based navigation
- **Expo Go**: Mobile app for testing

---

## Running the Application

```bash
# Start development server
npx expo start

# Start with cache cleared
npx expo start -c

# Run on iOS simulator (macOS only)
npx expo start --ios

# Run on Android emulator
npx expo start --android
```

---

## Troubleshooting

### QR Code Won't Scan
- Ensure phone and computer are on the same WiFi network
- Try running `npx expo start --tunnel`

### Metro Bundler Issues
- Run `npx expo start -c` to clear cache
- Delete `node_modules/` and run `npm install` again

### TypeScript Errors
- Ensure `npm install` has been run
- Check that all dependencies are installed

---

## Next Steps

After completing this task:
- ✅ Understand Expo project structure
- ✅ Know how to modify React Native screens
- ✅ Can run apps on physical devices
- ✅ Ready to learn React Native components and styling

---

**Status**: ✅ Completed  
**Date**: January 2026  
**Repository**: prodev-mobile-setup  
**Directory**: prodev-mobile-app-0x00
