# PiSomfy
The objectif of this project is to be able to control my Somfy shaders from my Raspberry Pi without using the official remote

## Want you need
The first step is to buy the needed hardware.
1. **Transmitter**
- I took this one: [433MHz RF Transmitter Receiver Kit](https://www.ebay.ch/itm/272993898467?ViewItem=&item=272993898467). 
- There is 5 transmitters and receivers in this kit, useful and cheap.
2. **Crystals**
- As Somfy as a particular frequency to avoid noises, I found out that it's needed to change the crystal. 
- I took this one: [433.42M 433.42MHz R433 F433 SAW Resonator Crystals TO-39](https://www.ebay.ch/itm/232574365405?ViewItem=&item=232574365405). 
- There is 5 crystals also in this kit, useful and cheap too.
3. **Wires** 
- To easy plugs between the Raspberry Pi and the Transmitter. I had in stock some [Male to Female Solderless Flexible Breadboard Jumper Cable Wire for Raspberry Pi](https://www.amazon.com/Ganvol-Flexible-Breadboard-Raspberry-ordinateur/dp/B01LVVIOUO) but they were Male to Female...so I had to customized them. 
- Otherwise, you can buy directly [Female to Female Solderless Flexible Breadboard Jumper Cable Wire for Raspberry Pi](https://www.amazon.com/Ganvol-Flexible-Breadboard-Raspberry-ordinateur/dp/B01LWAXJJS)

## Preparation
Now it's time for the setup.

### Soldering
You can now replace carefully your crystal

### Plug-in time
There are three pins on the transmitter: 
1. ATAD (DATA)
2. VCC
3. GND (Ground)

You need to connect all of them to the [Raspberry Pi GPIO.](https://www.raspberrypi.org/documentation/usage/gpio/)
1. Connect the ATAD pin with GPIO 4 (or adapt for your needs)
2. VCC with 5V
3. GND with any GND pin on the Raspberry Pi

## Coding
To be continued
