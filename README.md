# openwrt-rpi4b

Debian10 amd64/arm64 编译 OpenWrt树莓派4B固件 基于 [官方原版](https://github.com/openwrt/openwrt) v21.02.0-rc4

- [x] luci-app-passwall (SSR/Xray) from [xiaorouji](https://github.com/xiaorouji/openwrt-passwall)
- [x] luci-app-ddnsto & luci-app-linkease from [linkease](https://github.com/linkease/nas-packages)
- [x] aria2 server & samba server & DLNA server
- [x] http proxy server (polipo) & reverse proxy server (frps)
- [x] 本地磁盘挂载界面 Mount Points & 磁盘暂停运转 luci-app-hd-idle
- [x] 命令行工具 fdisk + mkfs.exfat + mount.cifs + tcpdump
- [x] USB 网卡支持 RNDIS + RTL8153(rtl8152) & 网络唤醒工具 luci-app-wol
- [x] 默认开启 BBR 加速 (kmod-tcp-bbr) & DNS over HTTPS
- [x] luci-app-sqm [配置说明](https://openwrt.org/docs/guide-user/network/traffic-shaping/sqm)
- [x] 集成 [OpenClash](https://github.com/vernesong/OpenClash) 依赖 & opkg 软件源 [sjtu mirror](https://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc4)
