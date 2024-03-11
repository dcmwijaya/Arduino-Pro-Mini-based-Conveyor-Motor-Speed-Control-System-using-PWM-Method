[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?style=flat)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?logo=github&color=%23F7DF1E)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method)
![Project](https://img.shields.io/badge/Project-Arduino-light.svg?style=flat&logo=arduino&logoColor=white&color=%23F7DF1E)

# Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method
<strong>Solo Project: Conveyor Motor Speed Control System using PWM Method</strong><br><br>
Conveyor is a mechanical system used to move goods or materials from one place to another that is carried out continuously. The purpose of this project is to provide education to the wider community on how to make a simple mini conveyor. This project has been implemented and takes approximately 1 week. To adjust how fast the conveyor machine can move, you can use a potentiometer. To change the direction of movement of the conveyor machine as well as stop it, you can use a push button. The benefit of making this project is none other than to add insight. The results show that this system can function properly.

<br><br>

## Project Requirements
| Part | Description |
| --- | --- |
| Development Board | Arduino Pro Mini |
| Code Editor | Arduino IDE |
| Programmer Tools | PL2303 USB |
| Driver | USB-Serial PL2303 |
| Programming Language | C/C++ |
| Actuators | Gear Motor / Motor DC (x1) |
| Other Components | • Jumper cable (1 set)<br>• Adaptor DC 12V 2A (x1)<br>• Motor driver L298N (x1)<br>• Breadboard (x1)<br>• Potentiometer (x1)<br>• Push button 12 x 12 mm (x2)<br>• Wood stickers (1 set)<br>• Wood planks (x2) |

<br><br>

## Download & Install
1. Arduino IDE 

   <table><tr><td width="810">

   ```
   https://www.arduino.cc/en/software
   ```

   </td></tr></table><br>

2. USB-Serial PL2303 

   <table><tr><td width="810">
   
   ```
   https://bit.ly/PL2303_Driver
   ```

   </td></tr></table>
   
<br><br>

## Project Designs
<table>
<tr>
<th width="420">Block Diagram</th>
<th width="420">Pictorial Diagram</th>
</tr>
<tr>
<td><img src="https://github.com/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method/assets/54527592/70f96299-f34b-4791-a694-4b70d3ce8c13" alt="Block-Diagram"></td>
<td><img src="https://github.com/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method/assets/54527592/756f8fe3-f4f7-4a95-b416-0db4d1ba7c4d" alt="Pictorial-Diagram"></td>
</tr>
</table>
<table>
<tr>
<th width="840">Wiring</th>
</tr>
<tr>
<td><img src="https://github.com/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method/assets/54527592/ad9bb821-410c-43a4-babf-3d6f6bd9d68b" alt="Wiring"></td>
</tr>
</table>

<br><br>

## Arduino IDE Setup
1. Open the ``` Arduino IDE ``` first, then open this project by clicking ``` File ``` -> ``` Open ``` : 

   <table><tr><td width="810">
   
      ``` pwm_conveyor.ino ```

   </td></tr></table><br>
   
2. ``` Board Setup ``` in Arduino IDE

   <table>
      <tr><th width="810">

      How to setup the ``` Arduino Pro Mini ``` board
            
      </th></tr>
      <tr><td>
      
      Click ``` Tools ``` -> ``` Board ``` -> ``` Arduino AVR Boards ``` -> ``` Arduino Pro or Pro Mini ```

      </td></tr>
   </table><br>

3. ``` Change Processor ``` in Arduino IDE

   <table><tr><td width="810">
      
      Click ``` Tools ``` -> ``` Processor ``` -> ``` ATmega328P (5V, 16 MHz) ```

   </td></tr></table><br>

4. ``` Port Setup ``` in Arduino IDE

   <table><tr><td width="810">
      
      Click ``` Port ``` -> Choose according to your device port ``` (you can see in device manager) ```

   </td></tr></table><br>

5. Before uploading the program please click: ``` Verify ```.<br><br>

6. If there is no error in the program code, then please click: ``` Upload ```.<br><br>

7. Some things you need to do when using the ``` Arduino Pro Mini board ``` with ``` PL2303 USB ``` :

   <table><tr><td width="810">

      • ``` Arduino IDE ``` information: ``` Uploading... ``` -> immediately press the ``` RESET ``` button and release it.
      
      • Wait until the message appears: ```Done Uploading ``` -> ```The program is directly operated ```.

   </td></tr></table><br>

8. If there is still a problem when uploading the program, then try checking the ``` driver ``` / ``` port ``` / ``` others ``` section.

<br><br>

## Programmer Tools Setup: PL2303 USB
<img width="840" src="https://github.com/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method/assets/54527592/cb033083-004b-4ee4-afb1-3dbc1590fc3f"><br><br>

<strong>Notes:</strong>

   <table><tr><td width="840">

   • This ``` Arduino Pro Mini ``` is not equipped with a ``` USB port ```, so you need an additional device in the form of a ``` USB to TTL Serial ``` to connect to a laptop or PC. ``` USB to TTL Serial ``` like the ``` PL2303 USB ``` is commonly used as an intermediate medium for uploading programs.
   
   • You can see the wiring between the ``` PL2303 USB ``` and the ``` Arduino Pro Mini ``` board in the picture above.

   • To upload the program, besides using the ``` PL2303 USB ```, you can also use other programming tools such as: ``` CP2102 USB ```, ``` CH340 USB ```, or ``` FTDI USB ```. Based on experience, I admit that using the ``` FTDI USB ``` is much better than the ``` PL2303 USB ``` because the upload process can be done automatically without the need to press the ``` RESET ``` button.

   </td></tr></table><br><br>

## Get Started
1. Download and extract this repository.<br><br>
   
2. Make sure you have the necessary electronic components.<br><br>
   
3. Make sure your components are designed according to the diagram.<br><br>
   
4. Configure your device according to the settings above.<br><br>

5. Please enjoy [Done].

<br><br>

## Highlights
<img src="" alt="pwm_conveyor">

<br><br>

## Appreciation
If you find this work useful, please support this work as a token of appreciation to the author by clicking the ``` ⭐Star ``` button.

<br><br>

## LICENSE
MIT License - Copyright © 2024 - Devan C. M. Wijaya, S.Kom

Permission is hereby granted without charge to any person obtaining a copy of this software and the software-related documentation files to deal in them without restriction, including without limitation the right to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons receiving the Software to be furnished therewith on the following terms:

The above copyright notice and this permission notice must accompany all copies or substantial portions of the Software.

IN ANY EVENT, THE AUTHOR OR COPYRIGHT HOLDER HEREIN RETAINS FULL OWNERSHIP RIGHTS. THE SOFTWARE IS PROVIDED AS IS, WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, THEREFORE IF ANY DAMAGE, LOSS, OR OTHERWISE ARISES FROM THE USE OR OTHER DEALINGS IN THE SOFTWARE, THE AUTHOR OR COPYRIGHT HOLDER SHALL NOT BE LIABLE, AS THE USE OF THE SOFTWARE IS NOT COMPELLED AT ALL, SO THE RISK IS YOUR OWN.
