[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?style=flat)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?logo=github&color=%23F7DF1E)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method)
![Project](https://img.shields.io/badge/Project-Arduino-light.svg?style=flat&logo=arduino&logoColor=white&color=%23F7DF1E)

# Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method
<strong>Solo Project: Conveyor Motor Speed Control System using PWM Method</strong><br><br>
A conveyor is a mechanical system used to move goods or materials from one place to another which is done continuously. To set how fast the conveyor machine can move, you can use a potentiometer. As for adjusting the direction of motor movement (forward or backward), you can press the push button.

<br><br>

## Project Requirements
| Part | Description |
| --- | --- |
| Development Board | Arduino Pro Mini |
| Code Editor | Arduino IDE |
| Driver | USB-Serial PL2303 |
| Programming Language | C/C++ |
| Actuators | Gear Motor / Motor DC (x1) |
| Other Components | USB-Serial TTL: PL2303 (x1), Jumper cable (1 set), KCD11: Rocker Switch SPST (x1), Li-ion battery 18650 (x2), 2-Slot series battery holder (x1), Motor driver L298N (x1), Potensiometer (x1), and Push Button (x1) |

<br><br>

## Download & Install
1. Arduino IDE

   ```
   https://www.arduino.cc/en/software
   ```
<br>

2. USB-Serial PL2303

   ```
   https://bit.ly/PL2303_Driver
   ```
   
<br><br>

## Project Designs
<table>
<tr>
<th width="420">Block Diagram</th>
<th width="420">Pictorial Diagram</th>
</tr>
<tr>
<td><img src="" alt="Block-Diagram"></td>
<td><img src="" alt="Pictorial-Diagram"></td>
</tr>
</table>
<table>
<tr>
<th width="840">Wiring</th>
</tr>
<tr>
<td><img src="" alt="Wiring"></td>
</tr>
</table>

<br><br>

## Arduino IDE Setup
1. Open the ``` Arduino IDE ``` first, then open this project by clicking: ``` File ``` -> ``` Open ``` -> ``` pwm_conveyor.ino ```.<br><br>
   
2. ``` Board Setup ``` in Arduino IDE<br><br>
   • Method: click ``` Tools ``` -> ``` Board ``` -> ``` Arduino AVR Boards ``` -> ``` Arduino Pro or Pro Mini ```.<br><br>

3. ``` Change Processor ``` in Arduino IDE.<br><br>
   • Method: click ``` Tools ``` -> ``` Processor ``` -> ``` ATmega328P (5V, 16 MHz) ```.<br><br>

4. ``` Port Setup ``` in Arduino IDE<br><br>
   • Method: click ``` Port ``` -> Choose according to your device port ``` (you can see in device manager) ```.<br><br>

5. Before uploading the program please click: ``` Verify ```.<br><br>

6. If there is no error in the program code, then please click: ``` Upload ```.<br><br>

7. When you find the writing ``` Uploading ``` the first time in the ``` Arduino IDE ```, then you must immediately press the ``` Reset ``` button on the board used, this aims to successfully upload the program. Then if there are still problems, then try checking the ``` driver ``` / ``` port ``` / ``` other ``` section.<br><br>
   
8. Please enjoy [Done].

<br><br>

## Use of USB-Serial TTL: PL2303
Coming Soon....

<br><br>

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

## LICENSE
MIT License - Copyright (c) 2024 - Devan C. M. Wijaya, S.Kom

Permission is hereby granted without charge to any person obtaining a copy of this software and the software-related documentation files to deal in them without restriction, including without limitation the right to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons receiving the Software to be furnished therewith on the following terms:

The above copyright notice and this permission notice must accompany all copies or substantial portions of the Software.

IN ANY EVENT, THE AUTHOR OR COPYRIGHT HOLDER HEREIN RETAINS FULL OWNERSHIP RIGHTS. THE SOFTWARE IS PROVIDED AS IS, WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, THEREFORE IF ANY DAMAGE, LOSS, OR OTHERWISE ARISES FROM THE USE OR OTHER DEALINGS IN THE SOFTWARE, THE AUTHOR OR COPYRIGHT HOLDER SHALL NOT BE LIABLE, AS THE USE OF THE SOFTWARE IS NOT COMPELLED AT ALL, SO THE RISK IS YOUR OWN.
