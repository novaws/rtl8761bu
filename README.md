This file fix
Bluetooth: hci0: command tx timeout


backup old.
mv /lib/firmware/rtl_bt/rtl8761bu_fw.bin.zst /lib/firmware/rtl_bt/rtl8761bu_fw.bin.zst.old

install new
cp rtl8761b_mp_chip_bt40_fw_asic_rom_patch_new.dat /lib/firmware/rtl_bt/rtl8761bu_fw.bin

remove and insert dongle.
