# Illuminati

<img width="1920" height="1080" alt="Your paragraph text" src="https://github.com/user-attachments/assets/1eb744ce-50b4-46ae-ab34-bf2bef09671b" />


## Why did I build this 
I built this drafting triangle to improve my routing skills as well using the render feature , which I hadn't used yet also this scale has Wi-Fi and an inbuilt accelerometer which would allow the user to level


## Features 
* WiFi and Bluetooth 
* Inch and MM scale 
* Accelerometer 
* RGB LEDs 
* User-Assigned GPIO Switches 

## How to Use this 
First connect this device via usb-c cable to your pc then download MicroPython from https://micropython.org/download/RPI_PICO/ then download the python firmware file in `Firmware` then put it in the root of the pico folder that will appear if Micropython is successfull , Then the led will blink


*Note the firmware is untested

## PCB Layout

| PCB Layout | Schematic / Wiring |
| :---: | :---: |
| <img width="1560" height="797" alt="PCB Layout" src="https://github.com/user-attachments/assets/b451f2f6-c7fe-4a43-8f5a-b1d58720bfc2" /> | <img width="1227" height="796" alt="Schematic / Wiring" src="https://github.com/user-attachments/assets/9d2caa30-8804-4463-a50a-27e097d5739f" /> |

## PCB Render

| Front | Rear |
| :---: | :---: |
| <img width="1642" height="866" alt="Front PCB Render" src="https://github.com/user-attachments/assets/f23a03a2-a0a7-40a4-a16a-25aa6b8e13da" /> | <img width="1682" height="823" alt="Rear PCB Render" src="https://github.com/user-attachments/assets/73f27301-00c8-4397-82d9-badb9d806882" /> |

## Case

<p align="center">
  <img width="1920" height="1080" alt="Iluminati Case" src="https://github.com/user-attachments/assets/56bec5a2-9196-4479-8766-ebafde3fff1f" />
</p>


---

## BOM

| Item | Description | Quantity | Unit Price ($) | Total Price ($) | URL |
|------|-------------|----------|----------------|-----------------|-----|
| PCB+PCBA | Custom PCB Manufacturing (JLCPCB) | 1 | 73| 73 | https://jlcpcb.com |
| Case | 3D Printed Case (Will be Printed Myself) | 1 | 0.00 | 0.00 | https://hackclub.com |
| **TOTAL** |  |  |  | **73.00** |  |


## BOM PCBA 


| Comment | Designator | Footprint | LCSC | Quantity |
| :--- | :--- | :--- | :--- | ---: |
| 100nF | C1, C10, C12, C13, C15, C16, C17, C18, C19, C20, C22, C24, C25, C3, C5, C6 | C_0402_1005Metric | C1525 | 16 |
| 10k | R11, R3, R9 | R_0402_1005Metric | C11616 | 3 |
| 10uF | C4, C7 | C_0402_1005Metric | C15525 | 2 |
| 10uF | C23 | C_0603_1608Metric | C1691 | 1 |
| 10uF | C2 | C_0402_1005Metric | C15525 | 1 |
| 1K | R1, R10, R4 | R_0402_1005Metric | C11702 | 3 |
| 1N5819WS | D1 | D_SOD-323 | C2921026 | 1 |
| 22pF | C11, C9 | C_0402_1005Metric | C1555 | 2 |
| 22uF | C8 | C_0402_1005Metric | C105226 | 1 |
| 4.7k | R12, R13 | R_0402_1005Metric | C11663 | 2 |
| 470 | R2, R8 | R_0402_1005Metric | C25117 | 2 |
| 5k1 | R5, R6 | R_0402_1005Metric | C105873 | 2 |
| AP2112K-3.3 | U4 | SOT-23-5 | C23380830 | 1 |
| LED_PWR | D4 | LED_0603_1608Metric | C2287 | 1 |
| LED_USR | D5 | LED_0603_1608Metric | C2287 | 1 |
| LIS3DH | U6 | LGA-16_3x3mm_P0.5mm_LayoutBorder3x5y | C15134 | 1 |
| SW_Push | SW1 | KEY-SMD_4P-L4.7-W3.5-P1.70-LS5.5 | C2915174 | 1 |
| SW_RST | SW2 | KEY-SMD_4P-L4.7-W3.5-P1.70-LS5.5 | C2915174 | 1 |
| USB_C_Receptacle_USB2.0_14P | J2 | USB_C_Receptacle_GCT_USB4105-xx-A_16P_TopMnt_Horizontal | C183603 | 1 |
| W25Q32JVSSIQ_C179173 | U2 | SOIC-8_L5.3-W5.3-P1.27-LS8.0-BL | C179173 | 1 |
| X322512MSB4SI | X1 | Crystal_SMD_3225-4Pin_3.2x2.5mm | C9002 | 1 |
| USBLC6-2SC6 | U5 | SOT-23-6 |  | 1 |


## JLCPCB 

<img width="1876" height="798" alt="image" src="https://github.com/user-attachments/assets/d3bdfac8-fcb0-47c4-b718-3959f837a4fa" />
<img width="1022" height="662" alt="image" src="https://github.com/user-attachments/assets/37b3ea8f-8faf-4c79-9cb1-4a03f15a002e" />



