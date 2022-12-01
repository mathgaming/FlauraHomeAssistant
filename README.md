# FlauraHomeAssistant
A modified version of Flaura by Martin McMaker (https://www.thingiverse.com/thing:4921885)\
It uses Home Assistant instead of Blynk

## Story
I started this project at the end of May 2022 and have worked on it a bit on and off.
Then I saw the following thread and decided to publish my progress in case someone could use what I have made:  \
https://community.home-assistant.io/t/invitation-project-suggestion-an-automated-potted-plant/  \
Martin Vinter made the thread and put his design files here: https://github.com/MartinVinter/Flaura2 \
My version is currently 95% working. I have tested the software and works without deep sleep.
After adding deep sleep the pump control fails. It works around 80% of the time and for the remaining 20% it does not turn off the pump before it goes to sleep.

## Parts
I bought everything on AliExpress because they have the option to combine all items in one big package when shipped to the EU. (Tired of asking for sellers to resend small items that got lost in shipping) \
Martin McMaker explains the choice of parts in Flaura_Parts_List_V1_0.zip (https://www.thingiverse.com/thing:4921885/files) \
I did not want to order custom-made PCBs. I use a prototype board instead.
I use the ESP32 called "TTGO T-Energy" because it has low power usage in deep sleep mode and a 18650 battery holder

### Part list:
TTGO T-Energy (ESP with 18650 battery holder) https://www.aliexpress.us/item/2251832765415995.html \
Cheap 3.7V water pump (no longer available) https://www.aliexpress.us/item/3256802475972254.html \
Soil moisture sensor: https://www.aliexpress.us/item/2255800945582601.html \
Screws: https://www.aliexpress.us/item/3256803144062450.html \
Double-sided prototype PCB 5x7: https://www.aliexpress.us/item/3256803198038888.html \
Pin header female 20 pins https://www.aliexpress.us/item/3256801232229618.html \
JST connector female 6 pins with cable (For water level measurements): https://www.aliexpress.us/item/2251832768103991.html \
SM JST Connector 22AWG with cable (For pump power): https://www.aliexpress.us/item/3256802336067007.html \
MOSFET IRLZ44N https://www.aliexpress.us/item/3256802288029799.html \
Diodes: https://www.aliexpress.us/item/3256801270295638.html \
Resistors: https://www.aliexpress.us/item/2251832766343175.html \
PVC tubes 3x5 mm + 5x7 mm: https://www.aliexpress.us/item/3256801537788462.html / https://www.aliexpress.us/item/3256803040259072.html \
PTFE tube 2x4 mm: https://www.aliexpress.us/item/3256801790661137.html \
T-connectors for tubes 3.2mm https://www.aliexpress.us/item/3256801423686650.html
