# Workshop Quick Help Guide

## Credentials

The Raspberry PI is currently using the default credentials which are:
- `username` - **pi**
- `password` - **raspberry**

## USB Console Cable Commands

Enter the following commands in the command line in order to establish a connection to your Raspberry PI.

- Drivers for MacOS are available [here](http://www.prolific.com.tw/UserFiles/files/PL2303_Mac%20OSX%20Drv_V1_6_2_20190723(2).rar).
- `ls /dev/cu.*` - lists all of the available serial ports.
- `screen /dev/cu.usbserial 115200` - Connect to Raspberry PI using a baud rate of 115200

## Raspberry PI Commands

- `hostname -I` - returns IP Address of the Raspberry PI.
- `ssh-keygen -R <IP-ADDRESS>` - Entering this command will reset the remote host key on the PI. For more info check [here](https://www.raspberrypi.org/forums/viewtopic.php?t=104253).
- `ssh pi@<IP-ADDRESS>` - Entering this command in the command line will create a SSH connection between your computer and your pi. This is just another method to connect to the pi.
- `ssh-copy-id pi@<IP-ADDRESS>` - copys your public key to the PI. Used for ssh purposes
- `ssh-add -K ~/.ssh/id_rsa` - Store the passphrase for your key in the macOS Keychain. This will make it so that you don't have to enter the passphrase each time you connect to your Pi.

## GPIO Commands

- `man gpio` - provides the manual for the `wiringPI` library installed on the PI. This is a small command line application that allows us to control the `GPIO` pins from the command line.
- `gpio -g mode 2 output` - Sets `GPIO 2` pin as an OUTPUT pin.
- `gpio -g mode 2 input` - Sets `GPIO 2` pin as an INPUT pin.
- `gpio -g write 2 0` - Sets the `GPIO 2` pin `LOW` or `OFF`.
- `gpio -g write 2 1` - Sets the `GPIO 2` pin 'HIGH` or `ON`.
- `gpio readall` - Shows a table with the current value and status of the `GPIO` pins.

## Github Repo's 

- [SwiftyGPIO](https://github.com/uraimo/SwiftyGPIO) - A Swift library for hardware projects on Linux/ARM boards with support for GPIOs/SPI/I2C/PWM/UART/1Wire. We will use this library to access our `GPIO` pins.
- [Swish](https://github.com/thomaspaulmann/Swish) - Build Swift Projects on a Remote Machine within Xcode. We will use this library to build our Swift code from XCode to the Raspberry PI.

## Applications Used

- [Fritzing](http://fritzing.org/download/0.9.3b/mac-os-x-105/Fritzing0.9.3b.dmg) - Application used for viewing circuits and creating circuit diagrams.
- [balanaEtcher](https://www.balena.io/etcher/) - Application used to create disk images.
