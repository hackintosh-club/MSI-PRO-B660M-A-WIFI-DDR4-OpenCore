## MSI PRO B660M-A WIFI DDR4 黑苹果 OpenCore EFI

![image](Screenshot/Motherbord.jpg)

### [ENGLISH](https://github.com/hackintosh-club/MAG-B760M-MORTAR-OpenCore)


### OpenCore

[OpenCore 1.0.4](https://github.com/acidanthera/OpenCorePkg)


### macOS

- macOS Sequoia
- macOS Sonoma
- macOS Ventura
- macOS Monterey


### 硬件

- 芯片组: B660
- BIOS版本: 7D43v1E 2023-09-13
- 处理器: 英特尔12代 i5-12500
- 内存: 金士顿 16GB(8GB*2) DDR4 2666 Mhz
- 硬盘: 金百达 KP330 128G Windows
- 硬盘: 紫光 P5160-512G MacOS
- 硬盘: 希捷 ST1000 1TB HDD
- 显卡: MSI AMD Radeon RX 6650 XT 8GB GDDR6
- 声卡: 瑞昱 ALC897
- 有线网卡: 瑞昱 RTL8125 Gaming 2.5GbE
- 无线网卡: BCM943602CS
- 处理器散热: 利民 AX120R
- 机箱:  先马（SAMA）易大师S1豪华版 黑色
- 电源:  海韵 FOCUS GX-750 金牌全模组


### BIOS设置

```
1.关闭安全启动
Settings
  |-- Security
     |-- Secure Boot
       |-- Secure Boot: Disabled

2.使用搜索功能查找并启用 D.T.M 
Search
  |-- D.T.M
    |-- D.T.M: Enabled

```

<img src="Screenshot/Search.png" alt="image" style="zoom:50%;" />

<img src="Screenshot/D.T.M.png" alt="image" style="zoom:50%;" />

<img src="Screenshot/SecureBoot.png" alt="image" style="zoom:50%;" />



### 注意事项

 - 安装成功后必须使用 [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) 生成你自己的 SMBIOS


### 常用工具

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) AKA `OCAT`.
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA `OCC`.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.


### 联系我们

QQ Group: 23304408

![image](Screenshot/QRCode.png)
