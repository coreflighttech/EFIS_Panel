# EFIS Panel

How to upload Firmware to the Core Flight Tech. B737 EFIS Panel?

Please be careful while uploading. Uploading the wrong version can make your device totally useless.

	-Download the "Uploader" -> https://github.com/coreflighttech/Uploader
	-Close all applications and be sure Mobiflight is not running in the background
	-Connect EFIS via USB
	-Run Xloader.exe in the "Uploader"
	-Click "Hex File" selection button.
	-Search in your computer and select the "mobiflight_uno_9_0_0.hex" file
	-Select the device as "EFIS/NAV/COMM/ATC/ADF V1"
	-Com port is the USB port which EFIS connected
	-Click Upload button
		If Xloader still says "Uploading" after 1 min., disconnect the USB cable and then connect it
			-Select the device as "EFIS/NAV/COMM/ATC/ADF V2"
			-Check the Com Port is the USB port which connected to EFIS
			-Click Upload button
	
	-Follow loading config file to the MF.


Important Note: Interrupting communication while uploading, can damage your device MCU.

https://coreflighttech.com/product/boeing-737-efis-panel/

Any feedback, please leave an e-mail to info@coreflighttech.com
