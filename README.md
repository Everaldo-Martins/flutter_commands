# FLUTTER COMMANDS

## NATIVE SPLASH

### Run in terminal
```bash
flutter pub add --dev flutter_native_splash
```

### Insert into pubspec.yaml
```
flutter_native_splash:
  color: "#FFFFFF" #Change color
  image: assets/images/splash_logo.png # Change image splash
  android: true
  ios: true
  android_12:
    icon_background_color: "#FFFFFF" # Change background color
    image: assets/images/splash_logo.png # Change image splash
```
    
### Run in terminal
```bash
flutter pub run flutter_native_splash:create
```
---

## CREATE LAUCHER ICON

### Run in terminal
```bash
flutter pub add --dev flutter_launcher_icons 
```

### Insert into pubspec.yaml
```
flutter_launcher_icons:
  ios: true
  android: launcher_icon
  image_path: assets/images/splash_logo.png
  adaptive_icon_foreground: assets/images/splash_logo.png 
  adaptive_icon_background: "#FFFFFF"
```

### Run in terminal
```bash
flutter pub run flutter_launcher_icons:main
```
