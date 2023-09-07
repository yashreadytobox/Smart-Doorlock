# ****Smart Doorlock System with Multi-Authentication****

## **Description**

The Smart Doorlock System with Multi-Authentication is a robust security system designed for access control, specifically for securing buildings and premises. This project integrates various authentication methods and runs on a Raspberry Pi 4. It offers enhanced security with multi-factor authentication, intrusion alerts, and remote access control. The system's primary goal is to provide a highly secure and customizable access control solution that can be monitored and controlled remotely.

## Features

The project consists of several modules, each serving a specific purpose in the system. Here are some of the key modules:

- **RFID Authentication**: Allows access through RFID card authentication.
- **Face Recognition**: Utilizes advanced face recognition algorithms for authentication.
- **Fingerprint Scanner**: Provides biometric fingerprint authentication.
- **OTP Authentication**: Sends one-time passcodes to registered email addresses.
- **Solenoid Lock**: Controls the physical locking and unlocking of the door.
- **Camera Module**: Captures images for face recognition and intrusion alerts.
- **LCD Display**: Optional module for displaying system status or messages.

### Modules

Here are the modules included in the project:

1. **10_rfid_test_read_3.py**: Module for testing and reading RFID cards.
2. **11_solenoid.py**: Controls the solenoid lock, responsible for physical door locking and unlocking.
3. **12_rfid_test.py**: Module for testing RFID functionality.
4. **13_email_keypad_solenoid_otp.py**: Integrates email notifications, keypad input, solenoid control, and OTP authentication.
5. **14_mail_keypad_face_otp.py**: Combines email notifications, keypad input, face recognition, and OTP authentication.
6. **15_pir_image_mail.py**: Utilizes a PIR sensor for motion detection, captures images, and sends email notifications.
7. **16_face_trial.py**: A module dedicated to face recognition testing.
8. **17_fingerprint_init.py**: Initializes the fingerprint scanner module.
9. **18_fingerprint_init1.py**: Another module for initializing the fingerprint scanner.
10. **19_camera_rfid.py**: Combines camera functionality with RFID authentication.
11. **1_rfid_face_solenoid.py**: Integrates RFID, face recognition, and solenoid control for multi-factor authentication.
12. **20_camera_trial.py**: A module specifically for camera testing.
13. **21_lcd.py**: Controls the LCD display module for status and messages.
14. **22_otp_camera_keypad.py**: Integrates OTP authentication, camera functionality, and keypad input.
15. **23_takeImage.py**: Module for capturing images.
16. **24_email_solenoid_rfid.py**: Combines email notifications, solenoid control, and RFID authentication.
17. **2_fingerprint_solenoid.py**: Integrates fingerprint authentication with solenoid control.
18. **3_deepface_trial.py**: A module dedicated to deep learning-based face recognition testing.
19. **4_fingerprint_lcd.py**: Combines fingerprint authentication with LCD display for status information.
20. **5_keypad_randomInt.py**: Utilizes the keypad for entering random integers.
21. **6_otp_mail_camera_keypad.py**: Combines OTP authentication, email notifications, camera functionality, and keypad input.
22. **7_rfid_test_read_1.py**: Module for testing and reading RFID cards.
23. **8_rfid_fingerprint_keypad_otp_mail.py**: Integrates RFID, fingerprint authentication, keypad input, OTP authentication, and email notifications.
24. **9_rfid_test_read_2.py**: Another module for testing and reading RFID cards.

## **Usage**

Once the system is set up, you can use it to secure your premises with multi-factor authentication. Authorized users can gain access through RFID cards, face recognition, fingerprint scans, or OTPs sent to their registered email addresses. The system also generates intrusion alerts and provides remote control features for added security.

## **Contributing**

Contributions to the project are welcome. If you'd like to contribute, please follow these guidelines:

1. Fork the project.
2. Create your feature branch (**`git checkout -b feature/YourFeatureName`**).
3. Commit your changes (**`git commit -m 'Add some feature'`**).
4. Push to the branch (**`git push origin feature/YourFeatureName`**).
5. Open a pull request.
