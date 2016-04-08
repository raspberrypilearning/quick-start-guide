# Raspberry Pi Quick Start Guide

Got a Raspberry Pi? Great, let's get started by making sure you have all the cables and accessories before plugging them all in and logging in for the first time.

# Check you have the equipment you need
Before you plug anything into your Raspberry Pi, make sure that you have all the equipment listed [here](https://www.raspberrypi.org/learning/quick-start-guide/requirements/)

To get started with Raspberry Pi you also need an operating system. NOOBS (New Out Of the Box Software) is an easy operating system install manager for the Raspberry Pi. *Raspbian* is the operating system that we use with the Raspberry Pi which you can download and image to an SD card.

## Buy a preinstalled SD Card

The easiest way to get NOOBS or Raspbian is to buy an SD card with the software already installed, available at the [Swag Store](http://swag.raspberrypi.org/products/noobs-8gb-sd-card). Alternatively, if you have an SD card (8GB recommended), then you can download NOOBS or Raspbian for free and install it on your card.

# Format your SD Card

It is best to format your SD card on your computer or laptop before copying the NOOBS files onto it or adding the Raspbian image. To do this:

1. Visit the [SD Association’s website](http://www.sdcard.org/) and download [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) for either Windows or Mac.
1. Follow the instructions to install the software.
1. Insert your SD card into the computer or laptop’s SD card reader and make a note of the drive letter allocated to it, e.g. `G:/`
1. In SD Formatter, select the drive letter for your SD card and format it.

# Download & Drag and drop NOOBS files

1. Using a computer with an SD card reader, visit the official Raspberry Pi [Downloads page](http://www.raspberrypi.org/downloads/).
1. Click on NOOBS.
1. Click on the Download ZIP button under ‘NOOBS (offline and network install)’, and select a folder to save it to.
1. Extract the files from the zip.
1. Once your SD card has been formatted, drag all the files in the extracted NOOBS folder and drop them onto the SD card drive.
1. The necessary files will then be transferred to your SD card.
1. When this process has finished, safely remove the SD card and insert it into your Raspberry Pi.

  [![Download and install NOOBS video](https://i.vimeocdn.com/video/469685790_100x75.webp)](https://vimeo.com/90518800)

# Or download & image Raspbian
An alternative to using NOOBS to install Raspbian, is to download and install the image directly. This is a faster process and great if you need to image multiple cards for a workshop or class.

1. Using a computer with an SD card reader, visit the official Raspberry Pi [Downloads page](http://www.raspberrypi.org/downloads/).
1. Click on Raspbian.
. Click on the Download ZIP button under ‘Raspbian Jessie (full desktop image)’, and select a folder to save it to.
1. Extract the files from the zip.
1. Visit [Etcher.io](http://www.etcher.io/) and download and install the Etcher SD card image utility.
1. Run Etcher and select the Raspbian image you unzipped on your computer or laptop.
1. Then select the SD card drive. Note that the software may have already selected thr right drive.
1. Finally click **Burn** to transfer Raspbian to the SD card. You will see a progress bar that tells you how much is left to do. Once complete the utility will automatically eject or unmount the SD card so it is safe to remove it from the computer.

# Plugging in your Raspberry Pi
1. Begin by slotting your SD card into the SD card slot on the Raspberry Pi, which will only fit one way.
1. Next, plug in your USB keyboard and Mouse into the USB slots on the Raspberry Pi.
1. Make sure that your monitor or TV is turned on, and that you have selected the right input (e.g. HDMI 1, DVI, etc)
1. Then connect your HDMI cable from your Raspberry Pi to your monitor or TV.
1. If you intend to connect your Raspberry Pi to the internet, plug in an ethernet cable into the ethernet port next to the USB ports, otherwise skip this step.
1. When you are happy that you have plugged in all the cables and SD card required, finally plug in the micro usb power supply. This action will turn on and boot your Raspberry Pi.
1. If this is the first time your Raspberry Pi and SD card have been used, then you will have to select an operating system and configure it. Follow the [Software Download & Install Guide](writing-sd-card-image.md) to do this.

[![Setting Up Raspberry Pi screenshot](https://i.vimeocdn.com/video/482234224.webp?mw=1920&mh=108)](https://vimeo.com/91631396)

# First time you power on
1. Once you have plugged in the power cable to your Raspberry Pi it will boot and if you are using NOOBS a window will appear with a list of different operating systems that you can install. We recommend that you use Raspbian – tick the box next to Raspbian and click on `Install`.
1. Raspbian will then run through its installation process. *Note this can take a while.*
1. When the install process has completed, the Raspberry Pi configuration menu (`raspi-config`) will load. Here you are able to set the time and date for your region and enable a Raspberry Pi camera board, or even create users. You can exit this menu by using `Tab` on your keyboard to move to `Finish`.
1. If you image Raspbian then you will boot directly to the desktop environment of Raspbian and will not need to wait.

# What next?
- Learn how to [update your SD Card](update-sd-card.md)
- Connect your Raspberry Pi to [wifi](wifi.md)
- Install more [applications](install-apps.md)
