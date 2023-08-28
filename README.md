# quad-core-process-lowRISC-ariane
lowRISC <br>
<img src=./docs/diagrams/project_top.svg>

## Specification
|Component
|-----------|
|Num Core = 4
Frequency = 1 GHz
Cache Size = 16MB (L3)
Memory Size = 
Address Width = 64


|address            |register   |device   |description
|-------------------|-----------|---------|-----------
|0x00000000_00000000|MEM START  |AXI SLAVE|text here
|0x000003FF_FFFFFFFF|MEM END    |AXI SLAVE|text here
|0x80000000_00001000|boot_addr_0|RIF      |text here
|0x80000000_00001008|boot_addr_1|RIF      |text here
|0x80000000_00001010|boot_addr_2|RIF      |text here
|0x80000000_00001018|boot_addr_3|RIF      |text here
|0x80000000_00002000|hart_id_0  |RIF      |text here
|0x80000000_00002008|hart_id_1  |RIF      |text here
|0x80000000_00002010|hart_id_2  |RIF      |text here
|0x80000000_00002018|hart_id_3  |RIF      |text here
|0x80000000_00003000|core_0_clk |RIF      |B0:      refdiv_i
||||B1: fbdiv_i
||||B2: fdiv_i
||||B3: bypass_i
||||B4: clk_en_0
||||B5, B6, B7: Reserved|
|0x80000000_00003008|core_1_clk |RIF      |B0:      refdiv_i
||||B1: fbdiv_i
||||B2: fdiv_i
||||B3: bypass_i
||||B4: clk_en_1
||||B5, B6, B7: Reserved|
|0x80000000_00003010|core_2_clk |RIF      |B0:      refdiv_i
||||B1: fbdiv_i
||||B2: fdiv_i
||||B3: bypass_i
||||B4: clk_en_2
||||B5, B6, B7: Reserved|
|0x80000000_00003018|core_2_clk |RIF      |B0:      refdiv_i
||||B1: fbdiv_i
||||B2: fdiv_i
||||B3: bypass_i
||||B4: clk_en_2
||||B5, B6, B7: Reserved|
