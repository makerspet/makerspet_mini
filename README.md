# Maker's Pet Mini ROS2 educational robot

A 124mm DIY 3D-printable pet robot compatible with [Kaia.ai](https://kaia.ai) software [platform](https://github.com/kaiaai/). 3D print, build, run and mod your own home pet robot! Please learn more at [Maker's Pet](https://makerspet.com), [REMAKE.AI](https://remake.ai) and join our [FB group](https://www.facebook.com/groups/243730868651472/).

Questions? Please visit the [Support Forum](https://github.com/makerspet/support/discussions/)!

Please install these Arduino libraries (using Arduino Library Manager) before building this firmware:
- [micro_ros_kaia](https://github.com/kaiaai/micro_ros_arduino_kaiaai)
- [LDS](https://github.com/kaiaai/LDS/)
- [PID_Timed](https://github.com/kaiaai/arduino_pid_timed)
- ESPAsyncWebSrv including AsyncTCP, ESPAsyncTCP

Supported laser distance scan sensors:
- YDLIDAR X4, X3, X3-PRO, X2/X2L
- Neato XV11
- LDS02RR from Xiaomi 1st gen vacuum cleaners (~$15 used off AliExpress including shipping)
- RPLIDAR A1

<p align="center">
  <img src="https://github.com/user-attachments/assets/a637f379-5ba2-4407-a00a-5fa81ebb6755" width="48%" alt="Mini robot in glossy red"/>
  <img src="https://github.com/user-attachments/assets/2b487792-3971-44b3-9905-d726304c440e" width="48%" alt="Mini robot in glossy purple"/> 
</p>

## Instructions videos - COMPLETE PLAYLIST
<a href="http://www.youtube.com/watch?feature=player_embedded&v=6GtjAB19GP8&list=PLOSXKDW70aR8uA1IFahSKVuk5ODDfjTZV" target="_blank">
 <img src="http://img.youtube.com/vi/6GtjAB19GP8/maxresdefault.jpg" alt="Watch the assembly instructions video" width="720" height="405" border="10" />
</a>

## Features
- room mapping using a 360-degree laser distance sensor (ROS2-based).
- autonomous self-driving (ROS2-based).
- code your character, skills (work in progress)
- 3D-printable, 200mm round base
- Arduino ESP32 micro-controller

## Instructions
- 3D printing [STL](https://github.com/makerspet/3d_models/tree/main/loki_200mm/stl), [3MF](https://github.com/makerspet/3d_models/tree/main/loki_200mm/3mf)
- Arduino ESP32 [firmware](https://github.com/kaiaai/firmware)
- PC end user and developer [setup](https://github.com/kaiaai/docker)
- KiCad [schematic, PCB](https://github.com/makerspet/pcb)
- Software setup, configuration [instructions](https://www.youtube.com/playlist?list=PLOSXKDW70aR8SA16wTB0ou9ClKhv7micy)
- Fusion 360 3D CAD [design files](https://github.com/makerspet/3d_models/tree/main/loki_200mm/fusion360)
- ROS2 software mod [instructions](https://github.com/makerspet/makerspet_loki/tree/main/urdf)

## Open-source design
Authored in Fusion 360. Printed using a Prusa MK3S+.
