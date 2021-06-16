# **cycloneII**

**Device：EP2c5 Size：（28,14）**

.arch文件：芯片架构XML描述

.icd文件：延迟的XML描述

.xsd文件：用于验证上述两个XML文件的模式

| x\y  |                              0                               |                              1                               |                  2                  |                  3                  |                  4                  |                              5                               |                              6                               |                              7                               |                    8                     |                    9                     |                    10                    |                 11                  |                 12                  |                              13                              |                              14                              |      |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------------------------------: | :---------------------------------: | :---------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------------------------------------: | :--------------------------------------: | :--------------------------------------: | :---------------------------------: | :---------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--- |
|  0   |                                                              | **PLL**, Subtype: HSDI(Subloc:0)<br/>**CLKBUFBLOCK**, Subtype: EXTCLK(Subloc:1) | **IO**, Subtype: HIO(Subloc:01234)  |  **IO**, Subtype: HIO(Subloc:0123)  | **IO**, Subtype: HIO(Subloc:01234)  |              **IO**, Subtype: HIO(Subloc:0123)               | **IO**, Subtype: GLOBAL_CLK(Subloc:0123)<br>**CLKBUFBLOCK**, Subtype: GCLK_1_WIDE(Subloc:5678)<br>**CLK_DELAY_CTRL**, Subtype: HIO(Subloc:10111213)<br>**CLK_DELAY_CAL_CTRL**, Subtype: HIO(Subloc:9) |           **IO**, Subtype: DEDICATED_IO(Subloc:01)           | **IO**, Subtype: DEDICATED_IO(Subloc:01) | **IO**, Subtype: DEDICATED_IO(Subloc:01) | **IO**, Subtype: DEDICATED_IO(Subloc:01) |  **IO**, Subtype: HIO(Subloc:0123)  |  **IO**, Subtype: HIO(Subloc:0123)  |              **IO**, Subtype: HIO(Subloc:01234)              |                                                              | 0    |
|  1   | **IO**, Subtype: VIO(Subloc:01)<br>**IO**, Subtype: VIO_MIRRORED(Subloc:2) |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                | **JTAG**, Subtype: DEFAULT(Subloc:0)<br>**SPIBLOCK**, Subtype: DEFAULT(Subloc:2)<br>**CRCBLOCK**, Subtype: DEFAULT(Subloc:1) |                                          |                                          |                                          |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) | 1    |
|  2   |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              |                                          |                                          |                                          |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 2    |
|  3   | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:2) |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              |                                          |                                          |                                          |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) | 3    |
|  4   |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              |                                          |                                          |                                          |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 4    |
|  5   |               **IO**, Subtype: VIO(Subloc:01)                |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              |                                          |                                          |                                          |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) | 5    |
|  6   |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              |                                          |                                          |                                          |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 6    |
|  7   | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) | 7    |
|  8   |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 8    |
|  9   | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:2) | 9    |
|  10  |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 10   |
|  11  |                                                              |             **M4K**, Subtype: DEFAULT(Subloc:0)              | **M4K**, Subtype: DEFAULT(Subloc:0) | **M4K**, Subtype: DEFAULT(Subloc:0) | **M4K**, Subtype: DEFAULT(Subloc:0) |             **M4K**, Subtype: DEFAULT(Subloc:0)              |             **M4K**, Subtype: DEFAULT(Subloc:0)              |             **M4K**, Subtype: DEFAULT(Subloc:0)              |   **M4K**, Subtype: DEFAULT(Subloc:0)    |   **M4K**, Subtype: DEFAULT(Subloc:0)    |   **M4K**, Subtype: DEFAULT(Subloc:0)    | **M4K**, Subtype: DEFAULT(Subloc:0) | **M4K**, Subtype: DEFAULT(Subloc:0) |             **M4K**, Subtype: DEFAULT(Subloc:0)              |                                                              | 11   |
|  12  |               **IO**, Subtype: VIO(Subloc:01)                |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:2) | 12   |
|  13  |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 13   |
|  14  | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) | 14   |
|  15  |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 15   |
|  16  |                                                              |             **MAC**, Subtype: DEFAULT(Subloc:0)              | **MAC**, Subtype: DEFAULT(Subloc:0) | **MAC**, Subtype: DEFAULT(Subloc:0) | **MAC**, Subtype: DEFAULT(Subloc:0) |             **MAC**, Subtype: DEFAULT(Subloc:0)              |             **MAC**, Subtype: DEFAULT(Subloc:0)              |             **MAC**, Subtype: DEFAULT(Subloc:0)              |   **MAC**, Subtype: DEFAULT(Subloc:0)    |   **MAC**, Subtype: DEFAULT(Subloc:0)    |   **MAC**, Subtype: DEFAULT(Subloc:0)    | **MAC**, Subtype: DEFAULT(Subloc:0) | **MAC**, Subtype: DEFAULT(Subloc:0) |             **MAC**, Subtype: DEFAULT(Subloc:0)              |                                                              | 16   |
|  17  | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) | 17   |
|  18  |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 18   |
|  19  | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:2) | 19   |
|  20  |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 20   |
|  21  | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:2) | 21   |
|  22  |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 22   |
|  23  |                                                              |             **M4K**, Subtype: DEFAULT(Subloc:0)              | **M4K**, Subtype: DEFAULT(Subloc:0) | **M4K**, Subtype: DEFAULT(Subloc:0) | **M4K**, Subtype: DEFAULT(Subloc:0) |             **M4K**, Subtype: DEFAULT(Subloc:0)              |             **M4K**, Subtype: DEFAULT(Subloc:0)              |             **M4K**, Subtype: DEFAULT(Subloc:0)              |   **M4K**, Subtype: DEFAULT(Subloc:0)    |   **M4K**, Subtype: DEFAULT(Subloc:0)    |   **M4K**, Subtype: DEFAULT(Subloc:0)    | **M4K**, Subtype: DEFAULT(Subloc:0) | **M4K**, Subtype: DEFAULT(Subloc:0) |             **M4K**, Subtype: DEFAULT(Subloc:0)              |                                                              | 23   |
|  24  | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:2) |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) | 24   |
|  25  |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 25   |
|  26  | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:23) |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                | **IO**, Subtype: VIO(Subloc:01)<br/>**IO**, Subtype: VIO_MIRRORED(Subloc:2) | 26   |
|  27  |                                                              |               LAB, Subtype: DEFAULT(Subloc:0)                |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |               LAB, Subtype: DEFAULT(Subloc:0)                |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |     LAB, Subtype: DEFAULT(Subloc:0)      |   LAB, Subtype: DEFAULT(Subloc:0)   |   LAB, Subtype: DEFAULT(Subloc:0)   |               LAB, Subtype: DEFAULT(Subloc:0)                |                                                              | 27   |
|  28  |                                                              |               **IO**, Subtype: HIO(Subloc:01)                |   **IO**, Subtype: HIO(Subloc:01)   |  **IO**, Subtype: HIO(Subloc:0123)  |  **IO**, Subtype: HIO(Subloc:012)   | **IO**, Subtype: DEDICATED_IO(Subloc:0)<br/>**IO**, Subtype: HIO(Subloc:1234) | **IO**, Subtype: HIO(Subloc:01)<br/>**IO**, Subtype: DEDICATED_IO(Subloc:23) | **IO**, Subtype: GLOBAL_CLK(Subloc:0123)<br/>**CLKBUFBLOCK**, Subtype: GCLK_1_WIDE(Subloc:5678)<br/>**CLK_DELAY_CTRL**, Subtype: HIO(Subloc:10111213)<br/>**CLK_DELAY_CAL_CTRL**, Subtype: HIO(Subloc:9) |     **IO**, Subtype: HIO(Subloc:01)      |     **IO**, Subtype: HIO(Subloc:012)     |    **IO**, Subtype: HIO(Subloc:0123)     |  **IO**, Subtype: HIO(Subloc:0123)  | **IO**, Subtype: HIO(Subloc:01234)  | **PLL**, Subtype: HSDI(Subloc:0)<br/>**CLKBUFBLOCK**, Subtype: EXTCLK(Subloc:1) |                                                              | 28   |
|      |                              0                               |                              1                               |                  2                  |                  3                  |                  4                  |                              5                               |                              6                               |                              7                               |                    8                     |                    9                     |                    10                    |                 11                  |                 12                  |                              13                              |                              14                              |      |

# **LAB子模块**

1. Sub Block: LE_COMB, Subtype: DEFAULT

2. Sub Block: LE_FF, Subtype: DEFAULT

3. Sub Block: LE_COMB, Subtype: DEFAULT

4. Sub Block: LE_FF, Subtype: DEFAULT

5. Sub Block: LE_COMB, Subtype: DEFAULT

6. Sub Block: LE_FF, Subtype: DEFAULT

7. Sub Block: LE_COMB, Subtype: DEFAULT

8. Sub Block: LE_FF, Subtype: DEFAULT

9. Sub Block: LE_COMB, Subtype: DEFAULT

10. Sub Block: LE_FF, Subtype: DEFAULT

11. Sub Block: LE_COMB, Subtype: DEFAULT

12. Sub Block: LE_FF, Subtype: DEFAULT

13. Sub Block: LE_COMB, Subtype: DEFAULT

14. Sub Block: LE_FF, Subtype: DEFAULT

15. Sub Block: LE_COMB, Subtype: DEFAULT

16. Sub Block: LE_FF, Subtype: DEFAULT

17. Sub Block: LE_COMB, Subtype: DEFAULT

18. Sub Block: LE_FF, Subtype: DEFAULT

19. Sub Block: LE_COMB, Subtype: DEFAULT

20. Sub Block: LE_FF, Subtype: DEFAULT

21. Sub Block: LE_COMB, Subtype: DEFAULT

22. Sub Block: LE_FF, Subtype: DEFAULT

23. Sub Block: LE_COMB, Subtype: DEFAULT

24. Sub Block: LE_FF, Subtype: DEFAULT

25. Sub Block: LE_COMB, Subtype: DEFAULT

26. Sub Block: LE_FF, Subtype: DEFAULT

27. Sub Block: LE_COMB, Subtype: DEFAULT

28. Sub Block: LE_FF, Subtype: DEFAULT

29. Sub Block: LE_COMB, Subtype: DEFAULT

30. Sub Block: LE_FF, Subtype: DEFAULT

31. Sub Block: LE_COMB, Subtype: DEFAULT

32. Sub Block: LE_FF, Subtype: DEFAULT

    （1. Location X: 0, Y: 0, Subloc: 0）

# MAC子模块

1. Sub Block: MAC_MULT, Subtype: DEFAULT
2. Sub Block: MAC_OUT, Subtype: DEFAULT

（1. Location X: 0, Y: 0, Subloc: 0        

2. Location X: 0, Y: 0, Subloc: 1

   1.Location X: 0, Y: 0, Subloc: 2.Location X: 0, Y: 0, Subloc: 3）

|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |

