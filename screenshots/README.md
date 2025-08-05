# 📱 Screenshots Directory

This folder contains screenshots of the Happy Places Android app for the main README file.

## 📸 Required Screenshots

Please add the following screenshots to this folder:

1. **`login_screen.png`** - Login/Registration screen showing the authentication UI
2. **`main_screen.png`** - Main dashboard with the list of happy places
3. **`add_place.png`** - Add new happy place screen with form fields
4. **`detail_view.png`** - Happy place detail view showing all information
5. **`map_view.png`** - Map view showing happy places on Google Maps
6. **`swipe_actions.png`** - Demonstration of swipe-to-edit/delete gestures

## 🎯 Screenshot Guidelines

- **Resolution**: 1080x1920 pixels (9:16 ratio) or 1920x1080 (16:9 ratio)
- **Format**: PNG or JPG
- **Quality**: High resolution, clear and crisp
- **Content**: Show the most important features and UI elements
- **Device**: Use a modern Android device or emulator for consistent appearance

## 📱 How to Take Screenshots

1. **Using Android Studio Emulator**:
   - Run your app in the emulator
   - Use the camera icon in the emulator toolbar to capture screenshots
   - Save with descriptive names as listed above

2. **Using Physical Device**:
   - Use your device's screenshot function (usually Power + Volume Down)
   - Transfer screenshots to your computer
   - Rename them according to the list above

3. **Using ADB** (Advanced):
   ```bash
   adb shell screencap /sdcard/screenshot.png
   adb pull /sdcard/screenshot.png screenshots/
   ```

## 🔄 Updating README

After adding screenshots, update the main README.md file to reference them:

```markdown
## 📱 Screenshots

![Login Screen](screenshots/login_screen.png)
![Main Screen](screenshots/main_screen.png)
![Add Place](screenshots/add_place.png)
![Detail View](screenshots/detail_view.png)
![Map View](screenshots/map_view.png)
![Swipe Actions](screenshots/swipe_actions.png)
```

---

**Note**: Make sure all screenshots are high quality and showcase the app's best features! 