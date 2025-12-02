# Cybersecurity : CSN150 Jeremy Lugo

## Name of Project
ESP32CAM - Camera

## Purpose
Set up ESP32 and Arduino enviornment. Execute sketch "Camera". 

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation


##### Link: https://lastminuteengineers.com/getting-started-with-esp32-cam/ 


## Steps I followed
1. Plug in my ESP32CAM and make sure it is properly connected

2. Open Arduino IDE software to cennect to ESP32CAM

3. Go to website link :"https://lastminuteengineers.com/getting-started-with-esp32-cam/" and follow steps it provided for setup

4. Go to Arduino IDE and click "File" on the top left and then select "Examples" from the drop down menu, from there I looked for the "ESP32" option and that opens another drop down menu. I selected "Camera" and that gave me the "CameraWebServer.ino" sketch to apply.

5. Within the CameraWebServer.ino section, I updated the ssid and password sections to my personal wifi settings.

6. In the board_config.h section, I made sure to update the section by changing the camera model to "CAMERA_MODEL_AI_THINKER" from "CAMERA_MODEL_ESP_EYE"

7. I then uploaded the sketch to run on the ESP32CAM

8. After uploading successfully, I opened my serial monitor to check if the cam was connected to my wifi. By doing this, I pressed the "RST" button on my ESP32CAM and the serial monitor showed the connection status as successful. It provided the URL to connect to the cam. This was the connection message: WiFi connected Camera Ready! Use 'http://192.168.1.200' to connect

9. I copy and pasted the URL in my browsers search bar and it brought me to the cam's settings to stream. I took a screenshot to prove it's successful connection
    



## Final Report: CameraWebServer sketch was successful, smooth process. I did not run into any issues with the instructions I was provided from the link "https://lastminuteengineers.com/getting-started-with-esp32-cam/". Followed every step and it turned out a success. ESP32CAM was successfully able to stream from the camera.


