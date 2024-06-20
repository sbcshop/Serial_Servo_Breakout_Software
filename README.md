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

## Serial Servo Control Using GUI Software
- Download [Software for windows](https://github.com/sbcshop/Serial_Servo_Breakout_Software/tree/main/SB-SERIAL-SERVO%20Software) provided here in github and open GUI app you will see interface as shown below,

  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/gui_interface.png" width="598" height="376" />
  
- Connect Breakout to PC/laptop using Type C connector, along with Serial Servo Motors and 6-8.4V DC Adapter. Make sure to put jumper in USB mode operation as shown below,
  
  <img src="https://github.com/sbcshop/Serial_Servo_Breakout_Software/blob/main/images/usb_mode.jpg" width="319" height="247" />


- Now you will have to select correct COM port, which you can checkout from Device Manager

## Related Products  

  * [Serial Servo Pico HAT](https://shop.sb-components.co.uk/products/serial-servo-hat-for-pico?_pos=5&_sid=8d954c383&_ss=r)

    ![Serial_Servo_Pico_HAT](https://shop.sb-components.co.uk/cdn/shop/files/SerialServoPicoHAT.jpg?v=1698412993&width=150)
    
  * [Serial Servo Arduino Shield](https://shop.sb-components.co.uk/products/serial-servo-arduino-shield?_pos=4&_sid=8d954c383&_ss=r)

    ![Serial_Servo_Arduino_Shield](https://shop.sb-components.co.uk/cdn/shop/files/servomotoron.jpg?v=1698413149&width=150)

  * [Serial Servo ESP32](https://shop.sb-components.co.uk/products/serial-servo-based-on-esp32?_pos=6&_sid=8d954c383&_ss=r)

    ![Serial_Servo_ESP32](https://shop.sb-components.co.uk/cdn/shop/files/SerialServobasedonESP32.jpg?v=1698412841&width=150)
    
  * [Serial Servo Raspberry Pi HAT](https://shop.sb-components.co.uk/products/serial-servo-hat-for-raspberry-pi?_pos=7&_sid=8d954c383&_ss=r)

    ![Serial_Servo_Raspberry Pi_HAT](https://shop.sb-components.co.uk/cdn/shop/files/SerialServoRaspberryPiHAT.jpg?v=1698412485&width=150)



## Product License

This is ***open source*** product. Kindly check LICENSE.md file for more information.

Please contact support@sb-components.co.uk for technical support.
<p align="center">
  <img width="360" height="100" src="https://cdn.shopify.com/s/files/1/1217/2104/files/Logo_sb_component_3.png?v=1666086771&width=300">
</p>
