# openwrt-rpi4b
编译环境：Debian 10 ARM64 虚拟机
OpenWrt：官方原版 v21.02.0-rc1 <https://github.com/openwrt/openwrt>
适用设备：树莓派4B
新增功能：luci-app-passwall (for ssr) <https://github.com/xiaorouji/openwrt-passwall>

开启功能：
1. USB RNDIS 网卡支持：华为随身wifi USB直连上网
2. 命令行挂载samba：mount.cifs

opkg软件源建议手动配置为（🇨🇳）：
src/gz openwrt_core http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/targets/bcm27xx/bcm2711/packages
src/gz openwrt_base http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/packages/aarch64_cortex-a72/base
src/gz openwrt_luci http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/packages/aarch64_cortex-a72/luci
src/gz openwrt_packages http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/packages/aarch64_cortex-a72/packages
src/gz openwrt_routing http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/packages/aarch64_cortex-a72/routing
src/gz openwrt_telephony http://mirror.sjtu.edu.cn/openwrt/releases/21.02.0-rc1/packages/aarch64_cortex-a72/telephony
