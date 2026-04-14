This is a work in progress. The prototype has not confirmed to work or function well yet.
This design uses a 4 layer PCB which is very affordable at JLCPCB as long as the inner layers are 0.5oz. 

The module requires a 300uf~ bulk cap (perferrabily polymer) close to  VIN on the main PCB. 

<img width="1813" height="1238" alt="image" src="https://github.com/user-attachments/assets/92cbdb21-c4f5-47c0-8428-9e1179dfd525" />

Silkscreen is removed over certain sections of ground to improve heat transfer. A heatsink will be required on the backside depending on the required load. Use a non-conductive thermal tape to adhere the heatsink to the PCB as the VCC and GND vias are both exposed on the backside. If not in use, cover with kapton tape. I have to figure out how to get KiCad to only cover the VCC vias...
