# Smart Doorbell IoT Project

This project is an IoT-based smart doorbell and locking system integrated with an app for real-time management and monitoring. It includes functionalities such as:

- Live video streaming from the doorbell camera.
- Remote locking and unlocking of the door.
- Push notifications for doorbell presses and motion detection.
- Role-based access for homeowners and residents.
- Password and resident management features.

## Features

- **Live Video Feed**: Stream the live feed from the ESP32-CAM directly in the app.
- **Lock/Unlock**: Control the door lock remotely through the app.
- **Notifications**: Receive notifications when the doorbell is pressed or motion is detected.
- **User Roles**: Homeowners can manage residents and have exclusive settings options.
- **Message Display**: Send custom messages to an OLED display connected to the ESP32.
- **Integration with Firebase**: Manage data and real-time updates.

## Directory Structure

### Documentaion
This folder contains relative documentations like **wiring diagram** , flow chart , and some other important reports.

### app
This folder contains the flutter app files.

### all_hardware
This folder contains the hardware code. and a list of all arduino libraries used in the project. 
- [cameraFinal](all_hardware/cameraFinal) - Contains the code for the esp32-cam.
- [hardware_code_final](all_hardware/hardware_code_final) - Contains the code for the esp32.

### UNITEST
This folder contains unit tests for validating the functionality of individual hardware components such as:

- Distance sensor
- Display module
- Keypad

These tests ensure each component operates correctly before integration into the system.

### COMM UNITEST
This folder is dedicated to testing the communication between different parts of the system, including:

- Hardware and Firebase communication.
- App and Firebase interaction.
- End-to-end integration between app, Firebase, and hardware.

### gitignore
This file has igonored git files and folders.


## How to Set Up

### Prerequisites
- ESP32 and ESP32-CAM microcontrollers.
- Firebase project for authentication and database.
- Flutter installed for app development.


## Testing

### Hardware Unit Tests
1. Navigate to the UNITEST folder.
2. Run the unit tests to validate individual hardware components, such as the distance sensor, display module, and keypad.

### Communication Unit Tests
1. Navigate to the COMM UNITEST folder.
2. Execute the tests to verify the communication between:
   - Hardware and Firebase.
   - App and Firebase.
   - End-to-end system integration.

## Contribution
Contributions are welcome! Here's how you can help:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
	```bash
   git checkout -b feature-or-bugfix-name
   git add .
   git commit -m "Description of your changes"
   git push origin feature-or-bugfix-name
   ```
3. Open a pull request to merge your changes into the main branch.

Thank you for using the Smart Doorbell IoT Project! Your contributions and feedback are greatly appreciated.

