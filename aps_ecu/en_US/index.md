# APS ECU Plugin

# Description
This plugin pulls data from an APSystems' ECU to use it in Jeedom.

# Requirements
This plugin requires the PHP sockets module to be installed.

# Usage
Enter the local IP address and the connection port (default 8899). Save and the commands corresponding to the ECU and inverter type will be created.

## Available Commands

* Lifetime Power : Total Power produced from the beginning
* Today Power : Power produced today
* Imported Power : Currently Imported Power from the grid
* Last System Power : Total Power produced currently

For Each Inverter :

* Online : The inverter is online and communicating with the ECU
* Frequency : Grid Frequency
* Temperature : Inverter's Temperature
* Radio Signal : Quality of the radio signal with the inverter
* Total Power : Total Power produced for each inverter
* Power : Power produced for each module connected to the inverter
* Voltage : Grid Voltage

## Caution
*The maximum power can not be detected with the ECU. You need to enter manually each maximum value for each inverter and module.*
