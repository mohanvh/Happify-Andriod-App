# 📱 Screenshots Directory

This folder contains screenshots of the Happy Places Android app for the main README file.

## 📸 Current Screenshots

The following screenshots are currently available in this folder:

1. **`login_screen.png`** - Login screen showing the authentication UI
2. **`registration_screen.png`** - User registration interface
3. **`main_screen.png`** - Main dashboard with the list of happy places
4. **`add_place.png`** - Add new happy place screen with form fields
5. **`detail_view.png`** - Happy place detail view showing all information
6. **`edit_action.png`** - Demonstration of swipe-to-edit gesture
7. **`delete_action.png`** - Demonstration of swipe-to-delete gesture

### Missing Screenshots (Optional):
- **`map_view.png`** - Map view showing happy places on Google Maps

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