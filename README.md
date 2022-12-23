# Marvin - the ultimate open-source rocket flight computer
## Suitable for middle to high power rockets.

>  - Yo, let's take whatever's left of our energy to live, and jam it into another flight computer, 
but this time let's make it posh and fix all the issues of the previous designs.
>  - No.
>  - We can use some pogo pin connectors.
>  - Fine.

![MarvinPic](/Marvin1BackMount2.png)

# Specs:
- 65x100mm 1.6mm thick PCB
- 168 Mhz STM32F407
- Separate power management chip ATTINY1607
- 3.3V, 5VPower, 5VExtension power buses
- Dual high current pyro channels with continuity detection circuitry
- 6 PWM outputs
- LSM6DSOTR IMU in sensor fusion configuration with LIS3MDLTR magnetometer
- Data logging to a 16 Mbit flash memory chip and/or micro SD card
- MS5611 pressure sensor, barometric altitude and BMP280 as a redundancy or the budget friendly option
- 32 free MCU breakout extension pins
- Short time of black box data logging after an unexpected power outage 
- The coolest debug connector ever
- Default 433 Mhz Ra-02 radio module (with proper antenna > 4 km open space range easily achievable)
- Status and power indication LED's
