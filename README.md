# Serial_Servo_Breakout_Software

<img src= "https://cdn.shopify.com/s/files/1/1217/2104/files/Artboard_1_5b49389d-44e7-43b4-8106-481d6ff27fe6.png?v=1718780960" />

The Serial Servo Breakout offers remarkable versatility, as it is compatible with a wide array of Single-Board Computers (SBCs) and microcontrollers. It possesses all the capabilities found in the Serial Servo Pico HAT or the Serial Servo Shield, allowing it to excel in a variety of applications. Its adaptability makes it an ideal choice for those seeking powerful servo control without the need for a display interface.
This Github provides getting started guide for Serial Servo Breakout.

## Features & Specification:
- Type C interface to use with Standalone GUI software
- UART breakout for interfacing with various Microcontrollers and SBCs.
- Screw terminal and DC jack for 6-8.4V adapter connect for servo motor supply
- Operating UART Voltage: 3.3V~5V (as per VCC)
- Operating Servo Voltage: 6~8.4V DC
- Status LED to indicate board power
- Jumper Selection to switch between direct USB and Breakout mode
- Onboard 4 Serial Servo Connectors, you can easily cascade to add more serial servo motors. Allows controlling 1-253 serial servos at the same time*
- Compatible Servo Motors =>
    - [SB-SS023](https://shop.sb-components.co.uk/products/sb-serial-servo-sb-ss023-powerful-multi-purpose-digital-servo-motor?_pos=1&_sid=5cba75e00&_ss=r) - For Lightweight Projects
    - [SB-SS15](https://shop.sb-components.co.uk/products/sb-serial-servo-sb-ss15-powerful-multi-purpose-digital-servo-motor?_pos=2&_sid=5cba75e00&_ss=r) - For Heavier Applications
    - Servo Motor Key Features:
      - Real-Time Position, Load, Temperature, Speed, and Voltage feedback.
      - Servo/Motor Mode Switchable
      - High Precision And Large Torque
      - ID Range 1~253
      - 38400 bps ~ 1Mbps (1Mbps by default)

***NOTE:  Avoid Connecting More Than 6 Servos At A Time, Not Recommended Due To High Current Demand By Servos.**

For more details about Serial Servo Motor checkout [Manual](https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/Documents/SB_Servo_User_Manual.pdf).

## Pinout
<img src= "https://cdn.shopify.com/s/files/1/1217/2104/files/Artboard_1_copy_5.png?v=1718801686" />

## Serial Servo Breakout with GUI Software
- Download [Software for windows](https://github.com/sbcshop/Serial_Servo_Breakout_Software/tree/main/SB-SERIAL-SERVO%20Software) provided here in github and open GUI app you will see interface as shown below,

  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/gui_interface.png" width="598" height="376" />
  
- Connect Breakout to PC/laptop using Type C connector, along with Serial Servo Motors and 6-8.4V DC Adapter. Make sure to put jumper in USB mode operation as shown below,
  
  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/usb_mode.jpg" width="" height=""/>

- Now you will have to select correct COM port, which you can checkout from Device Manager. Same COM port you need to select in GUI and click on connect button as shown,

  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/device_manager.jpg" width="582" height="424"/>

  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/gui_com_connect.jpg" width="598" height="376"/>
  
- Write Servo ID and click Read Button, then you have option to run in Motor or Servo Mode.

  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/connect_ID.jpg" width="598" height="376"/>
  
  **Motor Mode**
  
  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/motor_mode.jpg" width="598" height="376"/>

  **Servo Mode**
  
  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/servo_mode.jpg" width="598" height="376"/>
  
- You can search for ID of connected Servos from Parameters section and also you can try other options as well to Read/Write as shown below,

  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/servo_id_search.jpg" width="598" height="376"/>

## Serial Servo Breakout with MCU or SBC's

- To use Serial Servo Breakout change jumper position to set in UART mode as shown below,

  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/breakout_mode.jpg" width="276" height="229"/>
  
- Now follow below connection as per you MCU and make sure to proper VCC 3.3V/5V input which decides operating pin voltage. Then connect Servo motor and 6~8.4V DC supply.
  | MCU | Serial Servo Breakout |
  |---|---|
  |RXD | TXD|
  |TXD | RXD|
  |3.3V/5V | VCC|
  |GND | GND|

- For Getting Started Code you can checkout below githubs for some common MCU,
  - [Serial Servo with Pico](https://github.com/sbcshop/Serial_Servo_Pico_HAT_Software)
  - [Serial Servo with ESP32 MCU](https://github.com/sbcshop/Serial_Servo_ESP32_Software)
  - [Serial Servo with Arduino](https://github.com/sbcshop/Serial_Servo_Arduino_Shield_Software)
  - [Serial Servo with Raspberry Pi](https://github.com/sbcshop/Serial_Servo_RaspberryPi_HAT_Software)
  

## Related Products  

  * [Serial Servo Pico HAT](https://shop.sb-components.co.uk/products/serial-servo-pico-hat?_pos=5&_sid=1178c9361&_ss=r)

    ![Serial_Servo_Pico_HAT](https://shop.sb-components.co.uk/cdn/shop/files/Artboard2_1.png?v=1718781807&width=150)
    
  * [Serial Servo Arduino Shield](https://shop.sb-components.co.uk/products/serial-servo-arduino-shield-1?_pos=4&_sid=1178c9361&_ss=r)

    ![Serial_Servo_Arduino_Shield](https://shop.sb-components.co.uk/cdn/shop/files/Artboard2_3.png?v=1718793718&width=150)

  * [Serial Servo ESP32](https://shop.sb-components.co.uk/products/serial-servo-based-on-esp32-1?_pos=1&_sid=c593a9981&_ss=r)

    ![Serial_Servo_ESP32](https://shop.sb-components.co.uk/cdn/shop/files/esp322.png?v=1718797495&width=150)
    
  * [Serial Servo Raspberry Pi HAT](https://shop.sb-components.co.uk/products/serial-servo-raspberry-pi-hat?_pos=2&_sid=c593a9981&_ss=r)

    ![Serial_Servo_Raspberry Pi_HAT](https://shop.sb-components.co.uk/cdn/shop/files/Artboard2_2.png?v=1718788805&width=150)



## Product License

This is ***open source*** product. Kindly check LICENSE.md file for more information.

Please contact support@sb-components.co.uk for technical support.
<p align="center">
  <img width="360" height="100" src="https://cdn.shopify.com/s/files/1/1217/2104/files/Logo_sb_component_3.png?v=1666086771&width=300">
</p>
