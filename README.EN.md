# PI-SIGHT Helmet HUD

PI-SIGHT Helmet HUD is a head-up display device that is mounted on the outside of the helmet and displays necessary information in front of the user's eyes. The user can check necessary information or rear camera images through the display in front of his eyes without moving his head.

The biggest feature of the device is that it uses a small general-purpose computer, the Raspberry Pi, and a replaceable module system. This allows users to program the software themselves or replace it with the software they need, and by connecting a Bluetooth headset or GPS module, it can be used for various purposes such as navigation, racing instruments, and aviation instrument panels.


## function

 - Prism Display: You can check the necessary information without moving your head or holding a separate device through the 3000cd/m^2 display located in front of your eyes.
 - General-purpose system: Using the Raspberry Pi, a general-purpose Linux computer, you can easily develop and apply programs and sensors suited to your purpose.
 - Interchangeable module system: Allows easy replacement of programs and modules, allowing one device to be used for a variety of activities
 - For more information on the wireless remote control, rear camera, etc., please visit the [VUDEV website](https://sites.google.com/vudev.net/vudevnet/about-pi-sight) or download the [manual](https://github.com/Elenedeath/PI-SIGHT_Helmet_HUD/blob/main/PI-SIGHT%20%EC%82%AC%EC%9A%A9%EC%84%A4%EB%AA%85%EC%84%9C-1%20(%EB%94%94%EB%B0%94%EC%9D%B4%EC%8A%A4%20%EA%B8%B0%EB%B3%B8).EN.pdf).


## Software

 1. [Openauto](https://github.com/Elenedeath/PI-SIGHT_SW_Openauto): You can connect it to an Android smartphone and use it as an Android Auto head unit.
 2. [GPS Racer](https://github.com/Elenedeath/PI-SIGHT_SW_GPSRacer): It can be used as a self-lap timer or a Bluetooth GPS receiver that connects to a smartphone.
 3. [Rearview](https://github.com/Elenedeath/PI-SIGHT_SW_Rearview): Shows real-time rear camera video and automatically records during operation.
 - Anyone can create and use the programs and modules they need.


## How to make

 - Scheduled to be uploaded


## caution

 - _PI-SIGHT has not been sufficiently tested in various environments. You are free to create and use it, but we are not responsible for any problems that may arise as a result._
 - _PI-SIGHT does not support dustproofing or waterproofing. Please do not let water get in_
 - _If the tension adjustment bolt of the prism display is too loose, the display may move during use, which can be dangerous_


## Customizing

 - For wireless remote control firmware, refer to [PI-SIGHT Remote Controller SW](https://github.com/Elenedeath/PI-SIGHT_SW_RemoteController)
 - For PCB circuit and module connector, please refer to [Circuit](https://github.com/Elenedeath/PI-SIGHT_Helmet_HUD/blob/main/Documents/Circuits.pdf)
