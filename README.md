# HP / Agilent / Keysight 34420A

34420A 纳伏表/微欧表（一款1994年推出的7½位双通道纳伏微欧表）的用户手册和固件镜像。

## Manuals

**[34420A 用户手册](docs/34420A_Users_Manual.pdf)** — 共计 264 页，涵盖操作、编程、校准和维护维修。本手册汇集了所有五个已发布版本的内容。
Keysight（是德科技）发布的每个后续版本，其内容都不如之前的 Hewlett-Packard（惠普）版本详尽。而这份合并版手册不仅恢复了在第二版之后被删去的规格参数章节、规格参数应用指南以及电阻测量的快速入门部分；还整合了一份从未被正式并入任何官方版本的 SPRT（标准铂电阻温度计）手册更新内容；同时，将《服务指南》中的性能验证、校准调整和维修程序作为第 9 章和第 10 章补充在内。
手册中的所有插图均保留了原始版本的原貌。

**[34420A Technical Service Manual](docs/34420A_Technical_Service_Manual.pdf)**
— 86 pages covering the instrument's processor and memory system, firmware
organisation, remote command set and calibration data.

**[34420A Schematics](docs/34420A_Schematics.pdf)** — 13 sheets: the
component locators for the 34420-66501 and 34420-66502 boards, the block
diagram, and the ten schematic sheets from input and protection through to
the display and keyboard.

## Firmware

`firmware/` holds the three main-processor ROM images, 256 KB each, for
programming a 27C020 or equivalent.

| File | Part number | Revision |
|---|---|---|
| `HP_34420a_88851_REV5.0_Fw.bin` | 34420-88851 | 5.0 |
| `Agilent_34420-88871_REV9.0_Fw_AM27C020.bin` | 34420-88871 | 9.0 |
| `KS_34420-88872_REV10.0_fw_AT27C020.bin` | 34420-88872 | 10.0 |

---

Compiled by Jared Cabot, <jetstreamtechnology@protonmail.com>, with Claude
(Anthropic).

Not a publication of Hewlett-Packard, Agilent Technologies or Keysight
Technologies, not endorsed by them, and not a substitute for the
manufacturer's own documentation. Trade names are used for identification
only.
