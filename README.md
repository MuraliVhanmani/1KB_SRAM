# 1KB_SRAM
1KB SRAM — Full RTL-to-GDSII Physical Design Implementation  
Technology node: 45nm  
Tool flow used: RTL → Genus (synthesis) → Innovus (PnR) → GDSII  
version :  23.16-s070_1  

Type: Single-port synchronous SRAM (valid/ready handshake)  
Size: 1Kb (1024 bits) = 64 × 16  
Depth: 64 words  
Width: 16 bits/word  
Address width: 6 bits  
Reset: Synchronous, active-high  
  
# floor planning information    
Chip Area: 8145.072 µm²  
Core Area: 6418.656 µm²  
Standard Cell Area: 3609.810 µm² (excl. physical-only cells)  
Utilization: 57.24%  
Cell Count : 1173  

# Timing Closure Summary  
Setup:  WNS = 1.167 ns | TNS = 0.000 ns | Violating Paths = 0 / 562  
Hold:   WNS = 0.000 ns | TNS = 0.000 ns | Violating Paths = 0   
DRC Violations : 0 (max_cap, max_tran, max_fanout, max_length — all clean)  

# Power Summary 
Total Power: 0.314 mW  
 Internal Power:   0.221 mW (70.25%)  
 Switching Power:  0.093 mW (29.70%)  
 Leakage Power:    0.00017 mW (0.05%)  

Power by Category:  
 Sequential (flops): 58.69%  
 Clock network:      21.79%  
 Combinational:      19.53%  
  
Operating Frequency: 285.714 MHz (Clock Period = 3.5 ns)  

# VISUALS 
# floorplan  
  
<img width="1920" height="1080" alt="floorplan" src="https://github.com/user-attachments/assets/6d8f4d71-4676-4143-b3e9-fb9504271aee" />  
  
# port placement  

<img width="1920" height="1080" alt="port_placement" src="https://github.com/user-attachments/assets/8d4c2236-aa32-4087-bf9b-e79a442ac674" />  
  
# power plan  
  
<img width="1920" height="1080" alt="power_plan" src="https://github.com/user-attachments/assets/51fc6dcd-2bad-4680-9a5d-5aa9c3f38607" />  

# standard cell placed 

<img width="1920" height="1080" alt="standard_cells_placed" src="https://github.com/user-attachments/assets/ef71d86a-4cac-4c6c-ab3b-b65425ec4911" />  

# metal 9 to metal 1 all layers  

<img width="1920" height="1080" alt="layer9" src="https://github.com/user-attachments/assets/3f8e7873-c058-46e2-9e12-c667107e8c80" />  
<img width="1920" height="1080" alt="layer8" src="https://github.com/user-attachments/assets/734e750c-1eff-46a6-a982-2b9b61660c34" />  
<img width="1920" height="1080" alt="layer6" src="https://github.com/user-attachments/assets/6071a323-2aa3-46af-9c50-f5303637a259" />  
<img width="1920" height="1080" alt="layer5" src="https://github.com/user-attachments/assets/a7e73291-ed43-4959-bebe-82baec6110ef" />  
<img width="1920" height="1080" alt="layer4" src="https://github.com/user-attachments/assets/556b759f-6b2b-4877-a94f-cfd9fd29f75f" />  
<img width="1920" height="1080" alt="layer3" src="https://github.com/user-attachments/assets/6a8355bc-e4bb-4066-84d1-bb90da78963f" />  
<img width="1920" height="1080" alt="layer2" src="https://github.com/user-attachments/assets/94b885dc-c99d-4b41-ba42-9ac502d5f055" />  
<img width="1920" height="1080" alt="layer2" src="https://github.com/user-attachments/assets/7f143544-e027-45e3-bd3f-4b353da2a627" />  

# pre cts
 
<img width="1920" height="1080" alt="pre_cts" src="https://github.com/user-attachments/assets/45fc096e-3edd-4f55-a163-167bcc45b611" />  

# post cts


<img width="1920" height="1080" alt="post_cts" src="https://github.com/user-attachments/assets/a2395760-0ddb-4358-a48d-67031bf13313" />  

# Clock Tree


<img width="1920" height="1080" alt="clocktree" src="https://github.com/user-attachments/assets/e2886077-1b8c-41e9-b0c3-297077b713c0" />















