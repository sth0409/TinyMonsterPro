# GEEKON TinyMonster PRO Hackintosh EFI
TinyMonsterPro 黑苹果 EFI（基于黑果小兵的EFI）

TinyMonster Pro+i5-10600K+AX210

已通过日常使用测试

## 电脑配置

|   规格   |                           详细信息                           |
| :------: | :----------------------------------------------------------: |
| 电脑型号 |                       TinyMonster Pro                        |
| 操作系统 |                        macOS Monterey                         |
|  处理器  |                 英特尔 酷睿 i5-10600K                        |
|   内存   |                        16 GB 2933MHz                         |
| 硬盘1/2  |    Nvme Only: `XPG GAMMIX S11 Pro 1TB`/Nvme+SATA双协议插槽     |
| 硬盘3/4  |                 可接SATA 2.5寸硬盘/SATA SSD                  |
|   显卡   |       Intel UHD Graphics 630/可插独立显卡/独显独立供电       |
|   声卡   |                  Realtek ALC269 `alcid=33`                   |
|   网卡   |            m.2 NGFF插槽，已更换为`AX210`                  |

目前AX210在Monterey下蓝牙，WiFi驱动都正常。隔空传送等功能还不能用

## 相关链接

1. [CometLake CPU 相关配置说明](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#starting-point) 
2. [VRAM 相关配置](https://dortania.github.io/OpenCore-Post-Install/gpu-patching/intel-patching/vram.html#creating-our-patch)
3. [感谢黑果小兵的原版EFI](https://github.com/daliansky/TinyMonsterPro-Hackintosh)
