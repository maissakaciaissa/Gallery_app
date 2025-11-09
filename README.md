# Advanced Gallery App 📸

A simple Flutter image gallery application with grid and carousel view modes.

## Features ✨

- **Grid View**: Browse images in a 4-column grid layout
- **Carousel View**: Swipe through images with smooth animations
- **Full-Screen View**: Tap any image to view it in full screen with pinch-to-zoom
- **Delete Images**: Remove images from the gallery with confirmation dialogs
- **Smooth Transitions**: Animated view switching and page indicators

## Screenshots 📱

### Grid View
<img src="https://github.com/user-attachments/assets/acba405c-d372-4098-a281-71579d399aea" width="300">

### Carousel View
<img src="https://github.com/user-attachments/assets/1ff102d8-a595-414b-938b-c883af7f55b8" width="300">

### Full Screen View
<img src="https://github.com/user-attachments/assets/d54543b7-3ba5-4034-b57f-3765eccf34bf" width="300">


## Tech Stack 🛠️

- **Flutter**: Cross-platform mobile development
- **Material Design 3**: Modern UI components
- **Dart**: Programming language

## Note ⚠️

This is a **static gallery** application. Images are loaded from the `assets/images` directory and are defined in the code. The app does not support:
- Adding new images dynamically
- Importing images from device storage
- Persistent storage of deletions

## Getting Started 🚀

### Prerequisites

- Flutter SDK installed
- Android Studio / VS Code with Flutter extensions

### Installation

1. Clone the repository
```bash
git clone 
cd advanced_gallery
```

2. Add your images to the `images/` folder

3. Update `pubspec.yaml` to include your images:
```yaml

flutter:
  assets:
    - images/
```

4. Run the app
```bash
flutter run
```


## Usage 💡

- **Switch Views**: Tap the icon in the top-right corner to toggle between grid and carousel views
- **View Full Screen**: Tap any image to open it in full-screen mode
- **Navigate**: Use swipe gestures or arrow buttons to browse images
- **Zoom**: Pinch to zoom when viewing images in full screen
- **Delete**: Tap the delete icon and confirm to remove an image

## Customization 🎨

To modify the image list, edit the `imagePaths` array in `_ImageGalleryState`:

```dart
List<String> imagePaths = [
  'images/img1.jpg',
  'images/img2.jpg',
  // Add your images here
];
```

