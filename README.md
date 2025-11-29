# Driver-Drowsiness-Detection-using-hardware-
Driver Drowsiness Detection using ESP32cam,FTDI connector 
🚗 Driver Drowsiness Detection using ESP32-CAM

A real-time driver safety system built using ESP32-CAM to detect closed eyes / drowsiness and trigger alerts. The ESP32-CAM is programmed using FTDI connector and uses Eye Aspect Ratio (EAR) or image processing for detection.
📸 Hardware Used

ESP32-CAM (AI Thinker)

FTDI USB-to-TTL Programmer

Jumper wires

Power Supply 5V

(Optional) Buzzer / LED / Mobile Alert Integration



---

🧩 System Features

✔ Real-time eye detection
✔ Detects drowsiness
✔ Captures camera frames
✔ Sends alerts (LED/Buzzer/Phone message*)
✔ Works inside car environment


---

🔌 Wiring Diagram (ESP32-CAM + FTDI)

FTDI        ESP32-CAM
-------------------------
5V   --->   5V
GND  --->   GND
TX   --->   U0R
RX   --->   U0T
IO0  --->   GND  (IMPORTANT for Flash Mode)

To run normal mode: remove IO0 → GND after upload.


---

🛠️ Software Requirements

Arduino IDE

ESP32 Board Package

Required Libraries:

esp32-camera

WiFi.h

ESPAsyncWebServer (if web UI used)




---

▶️ How to Upload Code

1. Connect ESP32-CAM ↔ FTDI as shown


2. Hold IO0 to GND


3. Select:

Board: AI Thinker ESP32-CAM

Upload Speed: 115200

Flash Size: 4MB



4. Click Upload


5. After upload → remove IO0-GND jumper → press RESET



