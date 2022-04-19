# EFIS Panel

How to upload Firmware to the Core Flight Tech. B737 EFIS Panel?

Please be careful while uploading. Uploading the wrong version can make your device totally useless.

	-Close all applications and be sure X-Plane 11 is not running in the background. 
	-Connect MCP via USB. 
	-Run Xloader.exe 
	-Click "Hex File" selection button. 
	-Find correct .hex file. And then 
        -Select device as Duemilanove/Nano(ATmega328). 
	-Com port is the USB port which EFIS Panel connected. 
	-Check baud rate is 57600 and then upload the hex file. 
	
Important Note: While uploading, never interrupt the communication of the EFIS Panel. Otherwise, there is no way to recovery the unit if damaged.

https://coreflighttech.com/product/boeing-737-efis-panel/

Any feedback, please leave an e-mail to info@coreflighttech.com
