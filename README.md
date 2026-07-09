Full-wave bridge rectifier PCB designed in Altium. Converts AC into DC. Uses a smoothing capacitor and LED indicator. 

Filter cap: 1000uF 35V
Diodes: 1N4007

Schematic:
<img width="966" height="408" alt="image" src="https://github.com/user-attachments/assets/ee9bea62-0e58-48f6-8686-7e10c553c7f3" />

PCB Layout:
<img width="1450" height="755" alt="image" src="https://github.com/user-attachments/assets/140d015f-0a2f-40d1-812c-814d18271f6a" />

Simulation results shown in "results.png". 30V 20Hz AC input --> 28.2V peak DC output (drop due to diodes)
<img width="1858" height="1080" alt="image" src="https://github.com/user-attachments/assets/e0d02254-16d0-4e5e-a543-7be568b62f67" />


What I learnt/practiced: 
- More complex component placement
- Capacitor voltage rating must be higher than AC peak voltage
- Voltage drop across two series diodes
