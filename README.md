# Android Photos App

This Android Photos App is a port of the JavaFX Photos project, designed for seamless photo album management on Android devices. The app offers a range of features, including album creation, photo addition/removal, tagging, search functionality, and a user-friendly interface.

## Features

1. **Home Screen**: The app loads album and photo data from the previous session, listing all albums with names in plain text.
   
2. **Album Management**: Open, create, delete, and rename albums with ease. Opening an album displays all its photos with thumbnail images.

3. **Photo Management**: Within an open album, users can add, remove, or display a photo. The photo display screen includes an option for a slideshow, allowing for manual control of navigating backward or forward in the album.

4. **Tagging**: Users can add and delete tags to/from a photo, with only person and location being valid tag types. Tags are visible when displaying a photo.

5. **Photo Movement**: Move a photo from one album to another.

6. **Search Functionality**: Search for photos by tag-value pairs, limited to person and location tags. The search supports case-insensitivity, conjunction, disjunction, and auto-completion for tags.

7. **Storage Integration**: Save photos to the device's gallery.

## Implementation Notes

- The app is built using Android Studio with Java (not Kotlin).
- Minimum SDK version is set to Android 10.0 (API level 29).
- Target and compile SDK versions are set to API 34.
- The app is designed to run correctly on the Nexus 4 (4.7 inch, 768x1280, xhdpi) device emulator.

## Getting Started

1. Clone the repository using Git:

```bash
git clone [repository_url]
```

2. Open the project in Android Studio.

3. Build and run the app on the Nexus 4 emulator.

## Frequently Asked Questions

Refer to the FAQs section in the project description for additional information and clarification on certain aspects of the app.

## Contributing

Pull requests and bug reports are welcome. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the [MIT License](LICENSE.md).
