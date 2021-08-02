# openwrt-rpi4b

Debian10 amd64/arm64 编译 OpenWrt树莓派4B固件 基于 [官方原版](https://github.com/openwrt/openwrt) v21.02.0-rc4

- [x] luci-app-passwall (SSR/V2Ray) from [xiaorouji](https://github.com/xiaorouji/openwrt-passwall)
- [x] luci-app-ddnsto & luci-app-linkease from [linkease](https://github.com/linkease/nas-packages)
- [x] aria2 server (luci-app-aria2) & samba server (luci-app-samba4)
- [x] http proxy server (luci-app-polipo) & reverse proxy server (luci-app-frps)
- [x] 本地磁盘挂载界面 Mount Points & 磁盘暂停运转 luci-app-hd-idle
- [x] 命令行工具 fdisk + mkfs.exfat + mount.cifs
- [x] USB RNDIS & USB RTL8153(rtl8152) 网卡支持
- [x] 默认开启 BBR 加速 (kmod-tcp-bbr) & DNS over HTTPS (luci-app-https-dns-proxy)
- [x] luci-app-sqm [配置说明](https://openwrt.org/docs/guide-user/network/traffic-shaping/sqm)
- [x] 网络唤醒工具 luci-app-wol

opkg软件源建议手动配置为（🇨🇳）：
```
src/gz openwrt_core https://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc4/targets/bcm27xx/bcm2711/packages
src/gz openwrt_base https://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc4/packages/aarch64_cortex-a72/base
src/gz openwrt_luci https://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc4/packages/aarch64_cortex-a72/luci
src/gz openwrt_packages https://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc4/packages/aarch64_cortex-a72/packages
src/gz openwrt_routing https://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc4/packages/aarch64_cortex-a72/routing
src/gz openwrt_telephony https://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc4/packages/aarch64_cortex-a72/telephony
```
