# openwrt-bpi-r2
# try to add mt6625l support to openwrt

### test to armbian banana-pi-r2

##### Kernel v5.4.33	patches ok 

#### Firmware mediatek mt7623

	/system/etc/firmware/

	├── nvram
	│   └── WIFI
	├── ROMv2_lm_patch_1_0_hdr.bin
	├── ROMv2_lm_patch_1_1_hdr.bin
	├── WIFI_RAM_CODE_7623
	└── WMT_SOC.cfg


#### Patch FAILED

  	 Kernel v5.4.34	  Processing file /armbian/build/userpatches/kernel/mt7623-current/0102-dsa-mt7530-Extend-device-data.patch
			  1 out of 7 hunks FAILED -- saving rejects to file drivers/net/dsa/mt7530.c.rej

  	 Kernel v5.4-rc8  Processing file /armbian/build/userpatches/kernel/mt7623-current/0110-rtc-mt6397.patch
			  1 out of 7 hunks FAILED -- saving rejects to file drivers/rtc/rtc-mt6397.c.rej

