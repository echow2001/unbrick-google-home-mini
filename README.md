# google home mini unbrick

## Overview

the majority of the work is credited to courk at https://github.com/courk/NandBug-Software. The goal of this project is much simpler, instead of arbitary code execution this is just aims to rescue the not insignificant amount of google home mini devices bricked through bad firmware update or failing nand flash. The dump is read then corrected using the research from original project, and the device specific partitions are extracted and the firmware partitions replaced with known good data. Then this repaired dump is flashed onto the orignal nand if good and replaced. 
## Dumping the Flash
I am just using a TL866II plus to read/write to the nand along with a breakout board/socket. 
## Programming the Flash
again TL866II is used to interface with nand for simplicity. 
