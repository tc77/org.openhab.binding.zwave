---
layout: documentation
title: ZMNHJA - ZWave
---

{% include base.html %}

# ZMNHJA Flush Pilot
This describes the Z-Wave device *ZMNHJA*, manufactured by *[Goap](http://www.qubino.com/)* with the thing type UID of ```qubino_zmnhja_00_000```.

The device is in the category of *Wall Switch*, defining Any device attached to the wall that controls a binary status of something, for ex. a light switch.

![ZMNHJA product image](https://www.cd-jackson.com/zwave_device_uploads/354/354_default.png)


The ZMNHJA supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data from other devices.

## Overview

No device information is provided in the database. Consider [updating the database](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/354) to improve the documentation.

## Channels

The following table summarises the channels available for the ZMNHJA -:

| Channel | Channel Id | Category | Item Type |
|---------|------------|----------|-----------|
| Switch | switch_binary | Switch | Switch | 
| Dimmer | switch_dimmer | DimmableLight | Dimmer | 
| Sensor (temperature) | sensor_temperature | Temperature | Number:Temperature | 
| Binary Sensor 1 | sensor_binary1 | Door | Switch | 
| Binary Sensor 2 | sensor_binary2 | Door | Switch | 
| Binary Sensor 3 | sensor_binary3 | Door | Switch | 

### Switch

Switch the power on and off.

The ```switch_binary``` channel supports the ```Switch``` item and is in the ```Switch``` category.

### Dimmer

The brightness channel allows to control the brightness of a light.
            It is also possible to switch the light on and off.

The ```switch_dimmer``` channel supports the ```Dimmer``` item and is in the ```DimmableLight``` category.

### Sensor (temperature)

Indicates the current temperature.

The ```sensor_temperature``` channel supports the ```Number:Temperature``` item and is in the ```Temperature``` category.

### Binary Sensor 1

Indicates if a sensor has triggered.

The ```sensor_binary1``` channel supports the ```Switch``` item and is in the ```Door``` category. This is a read only channel so will only be updated following state changes from the device.

The following state translation is provided for this channel to the ```Switch``` item type -:

| Value | Label     |
|-------|-----------|
| ON | Triggered |
| OFF | Untriggered |

### Binary Sensor 2

Indicates if a sensor has triggered.

The ```sensor_binary2``` channel supports the ```Switch``` item and is in the ```Door``` category. This is a read only channel so will only be updated following state changes from the device.

The following state translation is provided for this channel to the ```Switch``` item type -:

| Value | Label     |
|-------|-----------|
| ON | Triggered |
| OFF | Untriggered |

### Binary Sensor 3

Indicates if a sensor has triggered.

The ```sensor_binary3``` channel supports the ```Switch``` item and is in the ```Door``` category. This is a read only channel so will only be updated following state changes from the device.

The following state translation is provided for this channel to the ```Switch``` item type -:

| Value | Label     |
|-------|-----------|
| ON | Triggered |
| OFF | Untriggered |



## Device Configuration

The following table provides a summary of the 10 configuration parameters available in the ZMNHJA.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Input 1 switch type |  |
| 2 | Input 2 switch type |  |
| 3 | Input 3 switch type |  |
| 4 | Input 1 contact type |  |
| 5 | Input 2 contact type |  |
| 6 | Input 3 contact type |  |
| 11 | Input 1 operation mode selection |  |
| 12 | Input 2 operation mode selection |  |
| 13 | Input 3 operation mode selection |  |
| 30 | Saving the state of the device after a power failure |  |
|  | Switch All Mode | Set the mode for the switch when receiving SWITCH ALL commands |

### Parameter 1: Input 1 switch type



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | mono-stable switch type (push button) |
| 1 | bi-stable switch type |

The manufacturer defined default value is ```1``` (bi-stable switch type).

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 2: Input 2 switch type



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | mono-stable switch type (push button) |
| 1 | bi-stable switch type |

The manufacturer defined default value is ```1``` (bi-stable switch type).

This parameter has the configuration ID ```config_2_1``` and is of type ```INTEGER```.


### Parameter 3: Input 3 switch type



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | mono-stable switch type (push button) |
| 1 | bi-stable switch type |

The manufacturer defined default value is ```1``` (bi-stable switch type).

This parameter has the configuration ID ```config_3_1``` and is of type ```INTEGER```.


### Parameter 4: Input 1 contact type



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | NO (normally open) input type |
| 1 | NC (normally close) input type |

The manufacturer defined default value is ```0``` (NO (normally open) input type).

This parameter has the configuration ID ```config_4_1``` and is of type ```INTEGER```.


### Parameter 5: Input 2 contact type



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | NO (normally open) input type |
| 1 | NC (normally close) input type |

The manufacturer defined default value is ```0``` (NO (normally open) input type).

This parameter has the configuration ID ```config_5_1``` and is of type ```INTEGER```.


### Parameter 6: Input 3 contact type



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | NO (normally open) input type |
| 1 | NC (normally close) input type |

The manufacturer defined default value is ```0``` (NO (normally open) input type).

This parameter has the configuration ID ```config_6_1``` and is of type ```INTEGER```.


### Parameter 11: Input 1 operation mode selection



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Button does not influence on selected mode |
| 1 | Comfort |
| 2 | Comfort-1°C |
| 3 | Comfort-2°C |
| 4 | Eco Mode |
| 5 | Frost Protection |
| 6 | Stop |

The manufacturer defined default value is ```1``` (Comfort).

This parameter has the configuration ID ```config_11_1``` and is of type ```INTEGER```.


### Parameter 12: Input 2 operation mode selection



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Button does not influence on selected mode |
| 1 | Comfort |
| 2 | Comfort-1°C |
| 3 | Comfort-2°C |
| 4 | Eco Mode |
| 5 | Frost Protection |
| 6 | Stop |

The manufacturer defined default value is ```4``` (Eco Mode).

This parameter has the configuration ID ```config_12_1``` and is of type ```INTEGER```.


### Parameter 13: Input 3 operation mode selection



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Button does not influence on selected mode |
| 1 | Comfort |
| 2 | Comfort-1°C |
| 3 | Comfort-2°C |
| 4 | Eco Mode |
| 5 | Frost Protection |
| 6 | Stop |

The manufacturer defined default value is ```5``` (Frost Protection).

This parameter has the configuration ID ```config_13_1``` and is of type ```INTEGER```.


### Parameter 30: Saving the state of the device after a power failure



The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | The module saves its state before power failure |
| 1 | The module does not save the state |

The manufacturer defined default value is ```0``` (The module saves its state before power failure).

This parameter has the configuration ID ```config_30_1``` and is of type ```INTEGER```.

### Switch All Mode

Set the mode for the switch when receiving SWITCH ALL commands.

The following option values may be configured -:
| Value  | Description |
|--------|-------------|
| 0 | Exclude from All On and All Off groups |
| 1 | Include in All On group |
| 2 | Include in All Off group |
| 255 | Include in All On and All Off groups |

This parameter has the configuration ID ```switchall_mode``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The ZMNHJA supports 5 association groups.

### Group 1: Lifeline group

This group supports 1 node.

### Group 2: Multilevel

This group supports 99 nodes.

### Group 3: Basic on/off 

This group supports 99 nodes.

### Group 4: Basic on/off

This group supports 99 nodes.

### Group 5: Basic on/off

This group supports 99 nodes.

## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SWITCH_BINARY_V1| |
| COMMAND_CLASS_SWITCH_MULTILEVEL_V3| Linked to BASIC|
| COMMAND_CLASS_SWITCH_ALL_V1| |
| COMMAND_CLASS_SENSOR_MULTILEVEL_V3| |
| COMMAND_CLASS_MULTI_CHANNEL_V2| |
| COMMAND_CLASS_CONFIGURATION_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_ASSOCIATION_V1| |
| COMMAND_CLASS_VERSION_V1| |
#### Endpoint 1

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_BINARY_V1| Linked to BASIC|
#### Endpoint 2

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_BINARY_V1| Linked to BASIC|
#### Endpoint 3

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_SENSOR_BINARY_V1| Linked to BASIC|

### Documentation Links

* [User Manual [French]](https://www.cd-jackson.com/zwave_device_uploads/354/Qubino-Flush-Pilot-wire-user-manual-V2-0-fra.pdf)
* [User Manual](https://www.cd-jackson.com/zwave_device_uploads/354/Qubino-Flush-pilot-wire-PLUS-user-manual-V1-1-eng.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/354).
