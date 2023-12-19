# AEP
Orion's Advanced Engines Pack for Spaceflight Simulator

Hi, and welcome to AEP! This document contains everything you need to know about this pack. 

# Recommended and required mods
N2O4s Electricity part pack (Required): https://github.com/DinitrogenTetroxide/sfs-electricity/releases/tag/v0.5

Proxima's PEx shapes+ (helps make your ships look cool to go with their fancy high-tech engines): https://jmnet.one/sfs/forum/index.php?threads/pex-shapes-a-different-kind-of-pack.13087/

NeptuneSky's VanillaUpgrades (helps with throttling the VASIMR and higher physics timewarp): https://jmnet.one/sfs/forum/index.php?threads/vanillaupgrades.9628/

Pixelgaming579's Smart SAS mod (For handling long prograde burns): https://jmnet.one/sfs/forum/index.php?threads/smart-sas-mod.10427/

# Download and installation
Step 1: download the .pack file

Step 2: paste the .pack file into the SFS parts folder, located in the mods folder in your game files

Step 3: load the game, and execute a realistic crewed Saturn mission (Optional, but cool.)

# Parts
This pack contains 6 different engines, all with their own specs and niches. All these engines are designed for realistic mode, but they should work well for realistic and normal. Each engine also has its own fuel requirments, eg. LH2 for the NERVA RNS and Xenon for the NEXT thruster. All the engines and fuel tanks can be found in the AEP folder in the parts menu.

# Engines

VASIMR:
The VASIMR (Variable Specific Impulse Magnetoplasma Rocket) is a special engine with the ability to shift gears, giving you high specific impulse and low thrust, or lower specific impulse and higher thrust. Change gears by changing the throttle, values given below.

Specs (Normal mode)

High gear:
  
  Isp = 19,400s
  
  Thrust = 0.025t
  
  Throttle % = 0.01%

Medium gear:
  
  Isp = 9,750s
  
  Thrust = 0.5t
  
  Throttle % = 20%

Low gear:
  
  Isp = 3,250s
  
  Thrust = 2.5t
  
  Throttle % = 100%

Mass = 0.45t

Fuel: Argon + Electricity

This engine will gobble electricity, so make sure you have about 48 large solar panels and a battery for a full range of operation.


Daedelus ICF:
This engine is a beast, the biggest in this pack. Originally intended for the second stage of an interstellar probe, this engine is perfect for sending whatever you want out of the solar system (or in it). Works by fusing He-3/Deuterium pellets roughly 250 times per second.

Specs (Normal mode)
  
  Isp = 720,599s
  
  Thrust = 70t
  
  Mass = 21.5t
  
  Fuel: He-3/Deuterium + Electricity
  
  Requires a tiny amount of electricity to ignite the fusion pellets.


NERVA RNS:
One of the most studied engines in this pack (researched by NASA and others since the 1950s), Nuclear Thermal Rockets almost flew as an upper stage engine for the Saturn V. This one was designed for a space tug that would transport material to the moon around 40 times before being discarded. Works by running LH2 over (usually) weapons-grade Uranium, heating up the propellant and giving you high exhaust velocities. TWR is horrible, so use in an upper stage.

Specs (Normal mode)
  
  Isp = 560s
  
  Thrust = 33.6t
  
  Mass = 18.7t
  
  Fuel: LH2


MPD Thruster:
One of the contenders for the propulsion of a manned mission to Saturn (and the engine that powered the Discovery 1 from 2001: A Space Odyssey), this souped up ion thruster combines (relatively) high thrust with high Isp. Also one of only two engines in this pack that has actually been tested in space.

Specs (Normal mode)
  
  Isp = 5,334s
  
  Thrust = 0.8t
  
  Mass = 0.1t
  
  Fuel: Lithium + Electricity
  
  You'll need about 16 large solar panels in order to keep this engine running for any reasonable amount of time.


Discovery II MCF:
Propulsion method for a NASA concept mission to Jupiter/Saturn in around a year of travel time. Interesting read, I'll add the study at the end.

Specs (Normal mode)
  
  Isp = 23,623s
  
  Thrust = 1.8t
  
  Mass = 6.5t
  
  Fuel: He-3/Deuterium


NEXT Thruster:
This is the second engine that has been tested in space, and was used in DART. Itès a gridded ion thruster, with slightly stockified values for mass and thrust. Later updates will likely give all of these engines more realistic mass and thrust values.

Specs (Normal mode)
  
  Isp = 2,780s
  
  Thrust = 0.5t
  
  Mass = 0.03t
  
  Fuel: Xenon + Electricity
  
  Requires a bit of electricity to operate. Two small solar panels per engine should suffice.

# Gallery

![Screenshot_2023-12-02_075526_1](https://github.com/Orion-CSAT/AEP/assets/150719581/362925ef-c1f9-4bae-89ed-417bdac92b86)
![Screenshot_2023-12-01_104657_1](https://github.com/Orion-CSAT/AEP/assets/150719581/46975f93-1af6-4336-9aab-37876ec85583)
![Screenshot_2023-11-22_104547](https://github.com/Orion-CSAT/AEP/assets/150719581/489601c0-a48c-409b-95a4-cfc7bf7e042e)
![Screenshot_2023-12-03_120303 (1)](https://github.com/Orion-CSAT/AEP/assets/150719581/85d66e1b-b5ec-4648-955d-e5aed8c7bad7)
![Screenshot_2023-12-03_111540](https://github.com/Orion-CSAT/AEP/assets/150719581/9b606873-1faa-435a-ad2f-bea98b11ab8d)
![Screenshot 2023-12-16 094019](https://github.com/Orion-CSAT/AEP/assets/150719581/59f0e3e7-4b78-4eaf-bd84-76a03aaf76c2)


# Further reading
VASIMR:
https://en.wikipedia.org/wiki/Variable_Specific_Impulse_Magnetoplasma_Rocket
https://www.adastrarocket.com/our-engine/
https://www.projectrho.com/public_html/rocket/enginelist.php#id--Electric--Electromagnetic_(Plasma)--VASIMR

MPD:
https://www.projectrho.com/public_html/rocket/enginelist.php#id--Electric--Electromagnetic_(Plasma)--Magnetoplasmadynamic_(MPD)
http://en.wikipedia.org/wiki/Magnetoplasmadynamic_thruster

Daedelus:
https://www.projectrho.com/public_html/rocket/slowerlight2.php#id--Go_Slow--Sublight_Starships--Project_Daedalus

Discovery II general info:
https://www.projectrho.com/public_html/rocket/realdesignsfusion.php#id--Discovery_II

Discovery II Original study:
http://naca.larc.nasa.gov/search.jsp?R=20050160960
