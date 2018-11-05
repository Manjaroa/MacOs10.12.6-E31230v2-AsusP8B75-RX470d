#### 配置
- CPU E3-1230v2
- 主板 P8B75-M LX PLUS
- 显卡 AMD RX470d

#### 工具
- Clover r4722
- Cloverconfiguratior
- U盘 + WeiPE
- Win10
- PcBeta.com
#### 安装盘开机boot cache修复
- **OsxAptioFix3Drv-64.efi** 放入 *drivers64UEFI* 文件夹
#### 显卡rx470d：
- **Lilu.kext** + **WhateverGreen.kext** 放入 *kexts/10.12*
#### 网卡RealtekRTF111F：
- **RealtekRTL8111.kext** 放入 *kexts/10.12*
#### 声卡realtek887：
万能驱动最新2.9.1版开机无爆音
- **VoodooHDA.kext** 放入 *kexts/10.12*
#### USB3.0：
- **GenericUSBXHCI.kext** 放入 *kexts/10.12*
#### CPU调频
共4挡
- clover设置 
    1. -xcpm
    2. 勾选 AppleIntelCPUPM
    3. SMBIOS设置: iMac13,1 Serial Number: C02JR3Y7DNCT
#### SSD开启TRIM

- clover设置
    KextsToPatch : Enable TRIM for SSD

