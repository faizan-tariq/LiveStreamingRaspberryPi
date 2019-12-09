# Goal: Live Streaming Using Pi
The Goal is to build live video streaming application using Raspberry Pi and its Camera Module.

## Getting Started with Raspberry Pi
We will cover what ever you need to setup and all the basic steps to follow when getting started with Raspberry Pi for the very 1st time. 

## What do you need?
- A Raspberry Pi board. For this tutorial I have Raspberry Pi 3 Model B with built-in WIFI and Bluetooth.
- Official Raspberry Pi Camera V2 Module. For this tutorial I ordered 'Sony IMX219 Light-sensitive Chips 8MP Pixels 1080P Video Original RPI 3 Camera'
- Acrylic case transparent Shell cover with Cooling Fan (Optional - just to prevent your circuit from getting heat up)
- Micro SD card for storage
- Power adapter or usb cable to power up your Raspberry Pi

## Assembly
You need to assemble as follows:

<p float="left">
<img src="https://github.com/faizan-tariq/LiveStreamingRaspberryPi/blob/master/2.png" width="200"/>
<img src="https://github.com/faizan-tariq/LiveStreamingRaspberryPi/blob/master/3.png" width="200"/>
<img src="https://github.com/faizan-tariq/LiveStreamingRaspberryPi/blob/master/4.png" width="200"/>
<img src="https://github.com/faizan-tariq/LiveStreamingRaspberryPi/blob/master/1.png" width="200"/>
</p>

## Operating System Installation
For this tutorial I downloaded and installed Raspbian OS for Raspberry PI. You can see the downloads on official raspberryPi site here: https://www.raspberrypi.org/downloads/raspbian/
You will need to download and install operating system on the mounted SD card.

### Steps
- Download the required OS from above mentioned link.
- Extract it and copy the files to sdcard.
- For the 1st time, Plug in your keyboard, mouse, and monitor cables.
- Insert micro SD Card into your Raspberry Pi, and plug the Pi into a power source.
- You will see an installer. You should check the box for Raspbian, and then click Install.
- The default login for Raspbian is username 'pi' with the password 'raspberry' if asked.

Details can be found here: https://projects.raspberrypi.org/en/projects/noobs-install

<img align="left" src="https://github.com/faizan-tariq/LiveStreamingRaspberryPi/blob/master/5.png" width="400">Once done you will be able to see the home screen as shown. Just notice the highlighted part i.e. make sure you have python installed, as we will be using python for writing scripts which can render live streaming straight from Camera to your display screen connected with Raspberry Pi. Normally it comes pre-installed with Raspbian.



