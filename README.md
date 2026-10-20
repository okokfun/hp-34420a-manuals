# HP / Agilent / Keysight 34420A

34420A 纳伏表/微欧表（一款1994年推出的7½位双通道纳伏微欧表）的用户手册和固件镜像。

## 手册

**[34420A 用户手册](docs/34420A_Users_Manual.pdf)** — 共计 264 页，涵盖操作、编程、校准和维护维修。本手册汇集了所有五个已发布版本的内容。
Keysight（是德科技）发布的每个后续版本，其内容都不如之前的 Hewlett-Packard（惠普）版本详尽。而这份合并版手册不仅恢复了在第二版之后被删去的规格参数章节、规格参数应用指南以及电阻测量的快速入门部分；还整合了一份从未被正式并入任何官方版本的 SPRT（标准铂电阻温度计）手册更新内容；同时，将《服务指南》中的性能验证、校准调整和维修程序作为第 9 章和第 10 章补充在内。
手册中的所有插图均保留了原始版本的原貌。

**[34420A 技术服务手册](docs/34420A_Technical_Service_Manual.pdf)**
— 共计 86 页，涵盖了该仪器的处理器与存储系统、固件架构、远程指令集以及校准数据。

**[34420A 电路原理图](docs/34420A_Schematics.pdf)** — 共 13 张图纸：包含 34420-66501 和 34420-66502 电路板的元件定位图、系统框图，以及从输入保护电路到显示器和键盘的 10 张电路原理图。

## 固件

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
