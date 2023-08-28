# quad-core-process-lowRISC-ariane
lowRISC <br>
<img src=./doc/diagrams/project_top.svg>

## Specification
|Component
|-----------|
|0x00000000_00000000|MEM START  |AXI SLAVE|text here
|0x000003FF_FFFFFFFF|MEM END    |AXI SLAVE|text here
|0x00000400_00001000|boot_addr_0|RIF      |text here
|0x00000400_00001004|boot_addr_1|RIF      |text here
|0x00000400_00001008|boot_addr_2|RIF      |text here
|0x00000400_0000100C|boot_addr_3|RIF      |text here
|0x00000400_00002000|hart_id_0  |RIF      |text here
|0x00000400_00002004|hart_id_1  |RIF      |text here
|0x00000400_00002008|hart_id_2  |RIF      |text here
|0x00000400_0000200C|hart_id_3  |RIF      |text here

|address            |register   |device   |description
|-------------------|-----------|---------|-----------
|0x00000000_00000000|MEM START  |AXI SLAVE|text here
|0x000003FF_FFFFFFFF|MEM END    |AXI SLAVE|text here
|0x80000000_00001000|boot_addr_0|RIF      |text here
|0x80000000_00001004|boot_addr_1|RIF      |text here
|0x80000000_00001008|boot_addr_2|RIF      |text here
|0x80000000_0000100C|boot_addr_3|RIF      |text here
|0x80000000_00002000|hart_id_0  |RIF      |text here
|0x80000000_00002004|hart_id_1  |RIF      |text here
|0x80000000_00002008|hart_id_2  |RIF      |text here
|0x80000000_0000200C|hart_id_3  |RIF      |text here