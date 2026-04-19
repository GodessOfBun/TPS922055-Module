### If you find this project helpful please consider buying me coffee
<a href="https://ko-fi.com/ameliabun">
<img width="56" height="56" alt="KofiRainbowMug_56" src="https://github.com/user-attachments/assets/bc97fb75-c19d-4fdd-86b4-e81835272c36" />
</a>
</br>
</br>
This is a work in progress. The prototype has not confirmed to work or function well yet.
This module is designed with 48v VIN in mind, but can be used for  any voltages lower, the inductor can be calculated for every scenario using https://www.schemalyzer.com/en/tools/buck-converter-calculator.
Default operation frequency is 1.2Mhz but can be lowered to 600KHz for lower heat if space allows.
This design uses a 4 layer PCB which is very affordable at JLCPCB as long as the inner layers are 0.5oz. 

The module requires a 300uf~ bulk cap (perferrabily polymer) close to  VIN on the main PCB. Ensure the area under the module is grounded to reduce EMI if possible.

<img width="1813" height="1238" alt="image" src="https://github.com/user-attachments/assets/92cbdb21-c4f5-47c0-8428-9e1179dfd525" />

Silkscreen is removed over certain sections of ground to improve heat transfer. A heatsink will be required on the backside depending on the required load. Use a non-conductive thermal tape to adhere the heatsink to the PCB as the VCC and GND vias are both exposed on the backside. If not in use, cover with kapton tape. I have to figure out how to get KiCad to only cover the VCC vias...
