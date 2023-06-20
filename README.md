# Finger-Print-Sensor-Lock

The fingerprint sensor lock system using Arduino and a solenoid lock addresses the need for reliable and convenient access control mechanisms. Traditional methods, such as key-based locks or keypad combinations, can be prone to security vulnerabilities or inconvenience. This project aims to provide a robust and user-friendly solution by leveraging biometric technology for secure authentication and a solenoid lock for physical security.

Fingerprint Sensor: The fingerprint sensor is a crucial component of the system. It captures the unique patterns and characteristics of an individual's fingerprints.

Arduino Board: An Arduino board serves as the central processing unit of the fingerprint sensor lock system. It communicates with the fingerprint sensor, stores and manages fingerprint templates, and controls the solenoid lock.

Solenoid Lock: The solenoid lock is a locking mechanism that ensures physical security by preventing unauthorized access. It can be controlled by the Arduino board to lock or unlock doors or other access points.

Relay Module: The relay module acts as a switch to control the power supply to the solenoid lock. It allows the low-power Arduino board to control the higher power requirements of the solenoid lock safely.

Authentication Workflow:
1. Fingerprint Enrollment: Authorized users' fingerprints are enrolled in the system by capturing multiple fingerprint samples. The Arduino board processes and stores these fingerprint templates in its memory.
2. Fingerprint Authentication: During authentication, a user places their finger on the fingerprint sensor. The sensor captures the fingerprint and compares it with the enrolled templates stored in the Arduino board's memory. If the captured fingerprint matches an authorized user's template, the authentication is successful.
3. Relay Control and Solenoid Lock Operation: Upon successful fingerprint authentication, the Arduino board sends a signal to control the relay module, which in turn switches the power supply to the solenoid lock. The lock is either unlocked or locked based on the authentication result.

Power Supply and Deployment:
The system can be powered using a stable power source, such as a mains power supply or a battery, with appropriate power management techniques. The relay module is connected to the Arduino board, and the solenoid lock is controlled via the relay module. The entire system can be housed in a secure enclosure suitable for the deployment environment.


Contributors:
Som Pratap Singh (Github ID - som-123)
Prateek Verma (Github ID - Prateek023)
