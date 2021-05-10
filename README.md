# openwrt-rpi4b

Debian10 ARM64 虚拟机环境下编译 OpenWrt树莓派4B固件 基于 [官方原版](https://github.com/openwrt/openwrt) v21.02.0-rc1

- [x] luci-app-passwall (for ssr) from [xiaorouji](https://github.com/xiaorouji/openwrt-passwall)
- [x] luci-app-ddnsto from [linkease](https://github.com/linkease/nas-packages)
- [x] 默认开启 BBR 加速：kmod-tcp-bbr
- [x] USB RNDIS 网卡支持：华为随身wifi USB直连上网
- [x] 命令行挂载 samba：mount.cifs

opkg软件源建议手动配置为（🇨🇳）：
```
src/gz openwrt_core http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/targets/bcm27xx/bcm2711/packages
src/gz openwrt_base http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/packages/aarch64_cortex-a72/base
src/gz openwrt_luci http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/packages/aarch64_cortex-a72/luci
src/gz openwrt_packages http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/packages/aarch64_cortex-a72/packages
src/gz openwrt_routing http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/packages/aarch64_cortex-a72/routing
src/gz openwrt_telephony http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/packages/aarch64_cortex-a72/telephony
```
