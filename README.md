💳 ATM Anti-Theft Security System
A smart, IoT-based security solution designed to prevent ATM robberies by detecting unauthorized tampering and triggering automated safety measures including door locking, real-time alerts, video surveillance, and GPS tracking.

📌 Abstract
With the rise in ATM-related thefts, this project aims to enhance ATM security by leveraging embedded systems, sensors, and IoT technologies. When a robbery attempt is detected through vibration sensors, the system automatically locks the ATM door, triggers a buzzer alarm, captures the scenario via camera, and sends the footage and GPS coordinates to nearby police and the associated bank.

🎯 Objectives
Prevent unauthorized access to ATMs.

Alert authorities in real time using GSM and GPS modules.

Automatically lock doors and record evidence.

Provide a formal step towards smart city infrastructure.

🛠️ Technologies & Components Used
Software
1.Python
2.Embedded C
3.OpenCV
4.NumPy
5.Machine Learning libraries

Hardware
1.Arduino board
2.Pi Camera Module
3.DC Motor
4.Servo Motor
5.LCD Display
6.Buzzer
7.Vibration Sensor
8.GPS Tracker
9.GSM Module

🔧 Features
* Vibration Detection: Identifies suspicious tampering using sensors.
* Automatic Locking: Servo/DC motors lock the door on intrusion detection.
* Alert System: Sends SMS alerts and emails with location data to police/bank.
* Video Surveillance: Captures and stores video during incidents.
* Gas Discharge Option: Unconscious intruders in extreme scenarios (simulated for prototype).
* LCD Status Display: Real-time feedback and system status updates.

🧪 How It Works
* Vibration detected → buzzer alerts surroundings.
* DC motor activates to lock ATM door.
* Camera records and streams to connected PC.
* GPS & GSM modules send alerts and location to police & bank.
* LCD module displays operational status.
* Keil tools used for motor control logic.
