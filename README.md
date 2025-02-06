# link_kickstart

## 自動化OS 安裝程式

## 以rocklinux 8.9為例，使用ISO 安裝後在設定檔設定如下
```
vmlinuz initrd=initrd.img inst.stage2=hd:LABEL=Rocky-8-9-x86_64-dvd inst.ks=https://github.com/tonyhsu0111/link_kickstart/blob/develop/default_ks.cfg
```

![image](https://github.com/tonyhsu0111/link_kickstart/blob/develop/step1.png)

![image](https://github.com/tonyhsu0111/link_kickstart/blob/develop/step2.png)