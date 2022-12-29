# Marvin - the [soon] ultimate open-source rocket flight computer
### Suitable for middle to high power rockets.

>  - Hey, let's take whatever's left of our energy to live, and jam it into another flight computer, 
but this time let's make it posh and fix all the issues of the previous designs.
>  - No.
>  - We can use some pogo pin connectors.
>  - Fine.

![MarvinPic](/MarvinFrontRender1.png)

# Specs:
- 65x100mm 1.6mm thick PCB
- 168Mhz STM32F407
- Separate power management chip ATTINY1607
- 3.3V, 5VPower, 5VExtension power buses
- Dual high current pyro channels with continuity detection circuitry
- 6 PWM outputs
- LSM6DSOTR IMU in sensor fusion configuration with LIS3MDLTR magnetometer
- MS5611 pressure sensor, barometric altitude and BMP280 as a redundancy or the budget friendly option
- Data logging to a 16Mbit flash memory chip and/or micro SD card
- 32 free GPIO
- Short time of black box data logging after an unexpected power outage 
- The coolest debug connector ever
- Default 433Mhz Ra-02 radio module (with proper antenna > 4km open space range easily achievable)
- Status and power indication LEDs

## Marvin is currently in testing phase, the schematics will likely change, but the development happens on our private server. Here, every version that gets put into production will be published.


Designed to fly a TVC rocket guided by artificial intelligence.
All the schematics and PCB files are available in the repo, but it Marvin flow yet. Once it becomes flight proven, official version will be released.

# Software

```
The software core is developed in a seperate repo, this one is only for the hardware part.
```
> https://github.com/3Fall/MarvinCore_r1


Co-developed with @Szum123321






