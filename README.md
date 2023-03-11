# raspberrypi-guide
A guide to using the raspberry pi microprocessor
Version : Raspberry Pi 3B+
# Specifications
Datasheet for reference: 
https://static.raspberrypi.org/files/product-briefs/Raspberry-Pi-Model-Bplus-Product-Brief.pdf

PROCESSOR CONFIGURATION : Broadcom BCM2837B0, Cortex-A53 64-bit SoC @ 1.4GHz <br/>
MEMORY: 1GB LPDDR2 SDRAM<br/>
INPUT POWER VOLTAGE : 5V/2.5A DC via micro USB connector<br/>
                      5V DC via GPIO header<br/>
                      Power over Ethernet (PoE)–enabled (requires separate PoE HAT)<br/>
A logic level converter should be used while connecting devices with an input level > 3.3V as the pi supports input voltage ranging from 1.8V-3.3V<br/>
A GPIO pin designated as an output pin can be set to high (3.3V) or low (0V). Components are usually attached so that setting the output to high will allow current to flow to them, while setting the output to low won’t. <br/>


# Initial-Setup
Flash the operating system version required on the SD (Memory) Card being used for the raspberry pi. 
