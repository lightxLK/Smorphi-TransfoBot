# The SMORPHI² TransfoBot

A transforming robot made in collaboration with **Wefaa Robotics** and **Singapore University of Technology and Design**, showcasing the _advancements in locomotion and the broad spectrum of Internet Of Things_ ( `IoT & Automation` ).

## Our Prestigious Mentors:
- Dr. Gyanaranjan Panigrahi
- Mr. Pritam Nanda
- Mr. Biswajeeban Mishra

## The Mighty Team:
- Sahil Kumar Chaudhury
- Tejaswinee Nayak
- Tanushree Lenka
- Choudhary Abisant Jena
- Rudra Narayan Behera
- Lokesh Patra ★
- Pallav Palai

>_" Every step and procedure was performed in alignment with the guidance of all the mentors and the esteemed panel from Wefaa Robotics, Singapore. "_

## Assembly Steps

### Step #1: Unpacking the smorphi² box
All the components were taken out of the box and spread on the floor. The components were:
- 16 x Mecanum Wheels (Right + Left)
- 4 x Aluminum Base Plates
- 8 x Acrylic Base Plates
- 16 x Mecanum Motors w/ Mounts 
- 6 x Solenoids w/ Latch Mount, Guide & Catch
- 6 x Hinge Mounts
- 3 x Hinge Mechanisms
- 1 x LiON Battery
- 2 x Battery Bracket
- 1 x Masterboard [ `Espressif32` ]
- 4 x [Slaveboard](https://github.com/WefaaRobotics/Smorphi/wiki/3.-Slaveboard)
- Multiple Sensors [Sound, Temperature, InfraRed] + HuskyCamera 
- Multiple Size Screws [`3 * 5 (x200)` + `3 * 10 (x45)` + `3 * 25 (x50)` + `4 * 8 (x15)`], 45 * M3 Nuts
- 32 x Hex MF M3 Nylon 45mm
- 28 x Hex FF M3 Nylon 10mm
- 8 x 4-pin Connectors + 4 x 8-pin Connectors
- 1 x USB Type C + 1 x Battery Charger
- 2 x Wing Screws [M3 * 5] + 1 x Ceramic Screwdriver + 1 Hex Key 1.5mm

### Step #2: Video Conferencing Session
Through the video conferencing session, we were given a link:  
[Smorphi-Documentation](https://smorphi-documentation.readthedocs.io/en/latest/)

- On the documentation website, there was a **Smorphi Assembly Manual** of different versions, as w/o and w/ Voltage Regulator with multiple purchase periods from:
  - [May '23 – September '23 – March '24 – August '24 – P R E S E N T]
- We chose the 3rd one, i.e., Smorphi² w/o Voltage Regulator [May '23 ~ August '24], and downloaded that manual.

### Step #3: Motor Sub-Assembly (A1 ; Pg. 7)
- Left & Right Mecanum Wheels are attached with their respective DC Motors, using motor mounts, shaft sleeve, and screws [M3 * 22].

### Step #4: Base Module Assembly (A2 ; Pg. 8)
- On an Aluminum Base Plate, there are 4 grooves numbered [1, 2, 3, 4].
- Inside those grooves, the wheels are inserted according to the odd-even layout as Right Wheels are Even Grooves [2 & 4], and Left Wheels are Odd Grooves [1 & 3].
- After fitting the wheels, Skirt Panels [A & B] are placed on the sides.
- Then, 4 x Hex M-F M3 Nylon 45mm Screws were tightened on the 4 corners of the Al Base Plate.

### Step #5: Solenoid Latch Sub-Assembly (A3 ; Pg. 11)
- On both sides of the Solenoid Latch, a latch mount and latch guide were attached with [M3 * 5] screws, similarly 6 latches were joined.

### Step #6: Mechanical Sub-Assembly (A4-7 ; Pg. 12-19)
- After assembling the parts respectively, now we got to assemble each module separately, according to the manual, in a very specific way of assembly of the 4 modules.
  - **Module 1:**
    - 2 Solenoid Latches are fitted between 1 – 2, and 4 – 3.
    - 1 Solenoid Catch is fitted between 1 – 4.
    - 1 Hinge Mount is fitted near the 4th corner of the Al Plate.
  - **Module 2:**
    - 1 Latch is fitted between 1 — 4.
    - 2 Catches are fitted between 1 – 2, and 4 – 3.
    - 2 Mounts are fitted near 2 corners, 1 & 4.
    - Battery Brackets are installed, in the middle, tightened with a Wing Screw, along with the battery.
  - **Module 3:**
    - 2 Latches are fitted between 1 – 2, and 4 – 3. 
    - 2 Catches are fitted between 1 – 4 and 2 – 3.
    - 2 Mounts are fitted near diagonal/odd corners, 1 & 3.
  - **Module 4:**
    - 1 Latch is fitted between 1 – 4.
    - 1 Catch is fitted between 4 – 3.
    - 1 Mount is fitted near the 4th corner.

### Step #7: Full Mechanical Assembly (A8 ; Pg. 20)
- All 4 modules are aligned together as [1 - M1 - 4] > [1 - M2 - 4] > [3 - M3 - 2] > [3 - M4 - 2], i.e., M3 & M4 are rotated **180°** from M1 & M2.
- After this alignment, the 4 modules are locked to each other, and the 3 hinges were attached to the hinge mounts.

### Step #8: E-Tray Sub-Assembly (B1 ; Pg. 24)
- Hex F-F M3 10mm holes were attached to the acrylic base plates with [M3 x 5] screws.
- Then, the slaveboards were attached onto those holes using more screws.

### Step #9: E-Tray onto Mechanical Assembly (B2 ; Pg. 25)
- The Motor Connectors on the Slaveboards are oriented with the Al base plate numbers, i.e., Motor 1 > 1, Motor 2 > 2, etc.

### Step #10: Motor Cable Connections (B3 ; Pg. 29)
- All DC Motors of the tires are connected to their respective Motor Connectors [M1 > MC1, etc.].

### Step #11: Solenoid Cable Connection (B4-7 ; Pg. 30)
- **Module 1:**
  - Latch [1 – 2] connected to Solenoid 1 Connector.
  - Latch [4 – 3] connected to Solenoid 2 Connector.
- **Module 2:**
  - Latch [1 – 4] connected to Solenoid 1 Connector.
- **Module 3:**
  - Latch [1 – 2] connected to Solenoid 2 Connector.
  - Latch [4 – 3] connected to Solenoid 1 Connector.
- **Module 4:**
  - Latch [1 – 4] connected to Solenoid 1 Connector.

### Step #12: InterModule Cable Connection (B8 ; Pg. 34)
- 3 * 8-Pin Wires are connected from Head to Tail Connectors of all the boards, as:
  - M1 – M2, & M2 – M3 are wired via 1 – 4 sides.
  - M3 – M4 is wired via inverse 1 – 4 side [180°].

### Step #13: Address Selection (B9 ; Pg. 35)
- The Ceramic Screwdriver was used to adjust the rotary switch for the respective address of each module as:
  - Module 1: Address 0
  - Module 2: Address 1
  - Module 3: Address 2
  - Module 4: Address 3

### Step #14: Masterboard E-Tray Sub-Assembly (B10 ; Pg. 36)
- Exactly as the Slaveboard attachment, the Masterboard is attached to an acrylic base plate, on **Module 2**.

### Step #15: Masterboard E-Tray onto Main Assembly (B11 ; Pg. 37)
- The header to the slaveboard connector on the Masterboard is aligned to face the 1 – 4 side of the slaveboard.
- Post-alignment, an 8-Pin wire is connected from [`Header to Masterboard`] to [`Header to Slaveboard`] connectors in both the boards, respectively.

### Step #16: Acrylic Covers (B12 ; Pg. 39)
- The rest of the modules [M1, M3, & M4] are attached with Acrylic Covers, using M3 x 5 screws.

### Step #17: Battery Connection (B13 ; Pg. 40)
- Ensuring the battery is fully charged, it was already placed in the Battery Bracket, and now its wire is connected to the Battery Connector on the Mainboard.
- Finally, the toggle switch is turned on, and if all the LEDs in all modules lit up, it was assured that all connections were properly made!
- After that, the ENABLE button is held for 1 second to activate the robot.

_<h4 align = 'center'> - smorphi² Assembly Complete -_ 


### Step #18: Application Connection
- The [Smorphi](https://play.google.com/store/apps/details?id=de.kai_morich.smorphi_app) application was installed on our smartphones, from PlayStore.
- After installing, we scanned the room through the app, using BLE ([Bluetooth Low Energy](https://github.com/WefaaRobotics/Smorphi/blob/V2.0_HT/Smorphi2/demo/Smorphi_Square_BLE_Demo/Smorphi_Square_BLE_Demo.ino)) technology.
- Once Smorphi is detected in the list, we connect to it and launch the controller.
- Then, we were introduced to various buttons as a JoyStick, several shape-transforming controls [`O`, `I`, `L`, `T`, `J`, `S`, `Z`], and 2 Pivot Turning buttons, which, when held, pivoted the robot in **clockwise** and **anti-clockwise** directions.

### Step #19: Sensor Configuration [Sound Sensor]
- A sound sensor was connected with a 4-pin cable to Module 1, GPIO0 port.
- Then, it was coded through Arduino IDE.
- For the programming purpose, the USB A to C cable was connected from the [Masterboard](https://github.com/WefaaRobotics/Smorphi/wiki/2.-Masterboard) to our laptop.
- The laptop was previously [set up with the necessary drivers](https://github.com/Biswajeeban/B.Tech.-IoT-V-July-2024/blob/Lokesh/Lokesh/Lab.%20Records/Lab%237_ESP32%20%F0%9F%90%BF%EF%B8%8F.md) [CP210x USB to UART Driver] and necessary libraries in the IDE.
- After the connection, [a sound sensor code](https://github.com/WefaaRobotics/Smorphi/blob/main/exercise/exercise_10/exercise_10.ino) was uploaded onto the laptop, and then our robot was ready to perform the Sound Sensory Acts.

_<h4 align = 'center'> - Disassembled -_
