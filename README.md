**Installing ESP8266 Board Support**
To program and work with ESP8266 microcontrollers using the Arduino IDE, you need to install the ESP8266 board support package. Follow these steps:

**Step 1: Add Board URL Link**



1 . Open Arduino IDE.
2. Go to File > Preferences.
3. In the "Additional Board Manager URLs" field, add the following URL:
bash
**http://arduino.esp8266.com/stable/package_esp8266com_index.json**
Click OK to close the Preferences window.


**Step 2: Install ESP8266 Board Package**
Navigate to Tools > Boards > Board Manager.
In the search bar, type "NodeMCU".
Find the package named "esp8266 by ESP8266 Community" and click on the Install button.
Wait for the installation process to complete.



**Step 3: Select ESP8266 Board** 

Once the installation is finished, go to Tools > Boards.
Select your ESP8266 board from the list. Common options include NodeMCU 1.0, Wemos D1 Mini, etc.
Step 4: Verify Installation
To verify that the installation was successful, connect your ESP8266 board to your computer.
Select the appropriate port from Tools > Port.
Open any example sketch or create a new one.
Upload the sketch to your ESP8266 board.
If the upload process completes without errors, the installation is successful.
You're now ready to develop and upload sketches to your ESP8266 board using the Arduino IDE!
