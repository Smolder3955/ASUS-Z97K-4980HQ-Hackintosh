# ASUS-Z97K-4980HQ-Hackintosh 
BGA转LGA

目前的问题:

HDMI音频无法使用

主板USB2.0识别为3.0

建议的BIOS设置:

高级:

CPU-处理器电源管理-CFG lock(关)

PCH-SATA模式-AHCI

VT-d(关)

USB-EHCI交接/XHCI(开)

内置设备-串口设置-串口(关)

监控:

处理器/机箱Q-fan根据情况设置(不要自动)

启动:

快速启动(关)

安全启动-操作系统-其它操作系统-密钥管理-清除默认密钥

按F10保存
