# 1KB_SRAM-
1KB SRAM — Full RTL-to-GDSII Physical Design Implementation  
Technology node: 45nm  
Tool flow used: RTL → Genus (synthesis) → Innovus (PnR) → gdsii  
version : 5.7  

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
DRC Violations (DRV): 0 (max_cap, max_tran, max_fanout, max_length — all clean)  

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

# visuals  
