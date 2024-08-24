This file fix
Bluetooth: hci0: command tx timeout

Quick
---
```bash
curl -sL https://gist.githubusercontent.com/novaws/456ffc308e4c2356b60fb2c21767ccef/raw/740de007b740da734194ce9c017aaa8ee27c358e/rtl8761bu_install.sh | bash -
```


Manual
---

backup old.
```bash
mv /lib/firmware/rtl_bt/rtl8761bu_fw.bin.zst /lib/firmware/rtl_bt/rtl8761bu_fw.bin.zst.old
```

install new
```bash
cp rtl8761b_mp_chip_bt40_fw_asic_rom_patch_new.dat /lib/firmware/rtl_bt/rtl8761bu_fw.bin
```

remove and insert dongle.
