# Introduction

<a href="url"><img src="./statics/reCamera.png" height="auto" width="auto" style="border-radius:40px"></a>

## ReCamera Core

ReCamera Core is a core module design based on SG2002 open source chip.
SG2002 equipped with high-performance RISC-V and ARM cores, it provides a fully open-source, ecosystem-rich deep learning vision processor that delivers 1.0 TOPS computing power@INT8.
s
<a href="url"><img src="./statics/SG2002.png" height="auto" width="auto" style="border-radius:10px"></a>

As the name suggests, this is an open source camera core board. The core board contains the core processor, EMMC storage, and WiFi chip. The core module led all the pins of the processor out through two BtoB sockets.
Through this interface, junior electronics engineers can customize their exclusive cameras by designing SensorBoard and BaseBoard.

<a href="url"><img src="./statics/BTB_Connector.png" height="auto" width="auto" style="border-radius:10px"></a>


## Application:

### [reCamera Gimbal](https://github.com/AllenKon/Seeed_reCamera_Gimbal)

Open source Gimbal solution made using reCamera.

<a href="url"><img src="./statics/reCamera-Gimbal.png" height="auto" width="auto" style="border-radius:40px"></a>

### [reCamera Robot Arm]()

waiting...

## SensorBoard

### S1_OV5647

> overview
> 
![img](./statics/S1_ov5647.png)

>schematic

![img](./statics/S1_ov5647_Sch.png)

> features:

- sensor
![alt text](./statics/S101_features.png)
- 4 x LED fill lights
- 1 x microphone
- 1 x speaker
- 3 x LED indicator

## BaseBoard
### B1_Default

### B2_POE





## Related Porjects:

[sscma Link](https://github.com/Seeed-Studio/sscma-example-sg200x)