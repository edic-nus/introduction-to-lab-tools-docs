# What is it? 
A controllable DC power source, especially useful when testing circuits. A key features of DC power supplies is the ability to set voltage and current limits, allowing you to test your circuit safely. 

# Setting voltage and current 
In general, you click the voltage/current button, select the decimal place you want to change, then turn the knob to the value you desire. However, the method to set voltage and current limits can vary, so you are **highly encouraged** to read the manual which is provided with yours. 

![dc_power_supply_image](./img/power_supply.jpg)

# Common terminology
- Device Under Test (DUT) - This refers to whatever device or circuit is currently being connected to the power supply and is commonly used in various fields related to electronics. 
- Constant Voltage (CV) - This is the default mode of a power supply; the voltage will remain stable at the value configured by the user. 
- Constant Current (CC) - When the DUT draws more current than the power supply can output the power supply will enter CC mode, dropping the voltage while maintaining current draw. This can occur because the physical limits of the power supply have been reached, or the current draw exceeded the value set by the user. 

# Limitations 
Every power supply will have its own maximum ratings, such as 30  V @ 150 W with a maximum current of 5 A. This could result in 'beefy' motors not functioning as intended when used with a power supply. Instead, a battery with much higher current ratings should be used, albeit cautiously. 

To combat this, multiple power supplies can be chained together in series or parallel in order to increase the total current or voltage output respectively. 
