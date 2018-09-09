
default: rpi-poe.dtbo

rpi-poe.dtbo: rpi-poe-overlay.dts
	dtc -@ -I dts -O dtb -o rpi-poe.dtbo rpi-poe-overlay.dts
