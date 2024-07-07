# TrackMate: Advanced Mobile Application for Real-Time Luggage Tracking

## Overview

**TrackMate** is an advanced mobile application designed for real-time luggage tracking and identification. This application integrates cutting-edge technology with user-friendly features to ensure a seamless luggage management experience. It utilizes hardware components like ESP32 and NEO-6M GPS modules, combined with robust software solutions, to provide real-time tracking, location updates, and additional functionalities to enhance user experience.

## Features

- **Real-Time Luggage Tracking**: Track the location of your luggage using the NEO-6M GPS module.
- **User-Friendly Interface**: Intuitive and easy-to-navigate interface for managing and tracking luggage.
- **Google Maps Integration**: Visualize luggage location on Google Maps.
- **Safeguard Functionality**: Set up safety features to receive notifications if the luggage moves out of a predefined area.
- **Directions**: Get directions to the location of your luggage using Google Maps.
- **Detailed Tracking Information**: View location coordinates, time stamps, and other relevant data.

## Technologies Used

- **Android Studio**: IDE for developing the mobile application.
- **Java/Kotlin**: Programming languages used for Android app development.
- **SQLite**: Local database management for storing luggage tracking data.
- **Google Maps API**: For displaying the location of the luggage on a map.
- **ESP32**: Microcontroller for handling communication between the mobile app and the GPS module.
- **NEO-6M GPS Module**: Hardware component for obtaining the GPS location data.

## Project Structure

```
TrackMate/
│
├── app/
│   ├── src/
│   ├── res/
│   ├── AndroidManifest.xml
│   └── build.gradle
│
├── hardware/
│   ├── ESP32/
│   ├── NEO-6M/
│   └── Circuit_Schematics/
│
├── documentation/
│   ├── API_Documentation/
│   └── User_Manual/
│
├── .gitignore
├── build.gradle
├── README.md
└── settings.gradle
```

## Usage

1. **Launch the App**: Open the TrackMate application on your Android device.
2. **Add Luggage**: Enter the details for the luggage you wish to track.
3. **Start Tracking**: Initiate tracking to get real-time location updates.
4. **View Location**: Check the location on Google Maps.
5. **Safeguard Feature**: Set up a safety zone for notifications.
6. **Get Directions**: Use the app to get directions to the luggage's location.

## Hardware Setup

1. **ESP32 Configuration**:
   - Connect the ESP32 to your computer via USB.
   - Upload the firmware code for communication with the NEO-6M GPS module.

2. **NEO-6M GPS Module Setup**:
   - Connect the NEO-6M GPS module to the ESP32.
   - Ensure proper wiring for power, ground, and serial communication.

3. **Circuit Schematics**:
   - Detailed circuit schematics can be found in the `hardware/Circuit_Schematics/` directory.
  
## Contributors

### [Sakshi Fadnavis](https://github.com/SakshiFadnavis2003)
- Backend development for the Android application.
- Integrated the NEO-6M GPS module and ESP32 hardware components with the mobile app.
- Designed and implemented server-side logic and APIs.

### [Khushi Bajpai](https://github.com/KhushiBajpai2003)
- Hardware design and development.
- Worked on the NEO-6M GPS module and ESP32 for real-time location tracking.
- Collaborated on the integration of hardware with the Android application.

### [Shruti Jain](https://github.com/shrutiijainn11)
- Frontend development for the Android application.
- Designed and implemented the user interface and user experience for the mobile app.
- Ensured the frontend interacted effectively with the backend and hardware components.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- **Email**: [fadnavissakshi@gmail.com](mailto:fadnavissakshi@gmail.com)
- **LinkedIn**: [Sakshi Fadnavis](https://www.linkedin.com/in/sakshi-fadnavis-3023a9240/)
- **Email**: [bajpaikv13@gmail.com](mailto:bajpaikv13@gmail.com)
- **LinkedIn**: [Khushi Bajpai](https://www.linkedin.com/in/khushi-bajpai-763605253/)
- **Email**: [jshruti034@gmail.com](mailto:jshruti034@gmail.com)
- **LinkedIn**: [Shruti Jain](https://www.linkedin.com/in/shruti-jain-b0b615225/)

