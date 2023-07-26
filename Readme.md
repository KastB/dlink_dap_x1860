# Image with additionall packages
currently: htop iperf nano and dawn

This image contains:
* luci
* wpad (full version)
* some network tools: iperf3 ethtool mtr knot-dig iwinfo
* dawn

This image DOES NOT contain:
* all PPP related packages: luci-proto-ppp ppp ppp-mod-pppoe kmod-pppox kmod-pppoe kmod-ppp wpad-basic-wolfssl

If you want to use this image just run:

```sysupgrade "https://github.com/KastB/dlink_dap_x1860/releases/latest/download/openwrt-ramips-mt7621-dlink-dap-x1860-a1-squashfs-sysupgrade.bin"```

Please note that I might change the packages included without notice. This image is built for my personnal use first.
