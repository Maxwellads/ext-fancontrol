# ext-fancontrol
A ulitity that allows to control fans that are supposed to cool devices which sensors are not detectable by system, in a way similar with fancontrol.

# Why ext-fancontrol?
Fancontrol enables the system to control fans in accrodance with the needs of reducing heat. While it is perfect for CPUs, it does not mean that every other device suits it. For example, if you are using a GPU that does not have internal fans, such as NVIDIA Tesla series cards, you may find that fancontrol does not have a reliable source of temperature readings of the card, causing GPUs overheat when running tasks requiring high GPU performance. 

# Pre-requirements
1. Your system supports controling fans by adjusting PWM, and your fan is connnected to the motherboard by a 4-pin slot.
2. Automatic mode for fans is disabled in BIOS/UEFI, or ext-fancontrol would not work(for now).
3. If you also have fancontrol running on your system, disable it or remove the fan from its configuration file (/etc/fancontrol).

# How to use
## Installation
## Generate configuration file
## Make it run on start up
