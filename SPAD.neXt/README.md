Special thanks to The1L2P (Discord ID: 1L2P#5598) for his excellent work!

# 2024-07-23 R20 release for SPAD 0.9.18.4+ 

CFT_737_EFIS_PANEL_SPAD_1L2P_R20_115200.ino.hex

- Serial device init improvements

Baud Rate is 115200

Internal devices features
- Turn on/off backlight by pressing FPV + MTRS
- Backlight brightness level setting by pressing FPV and turning BARO encoder
- Soft reset by pressing RST + STD
  
To manage backlight brightness from SPAD, search for this variable.
- BACKLIGHT_BRI : EFIS backlight brightness from 0 to 255 (DEVICE:1L2P/CFT737EFIS/BACKLIGHT_BRI)

Online SPAD complete device Snippet is #10856

![screenshot](https://user-images.githubusercontent.com/53659578/193854791-ab4db9c9-fb3a-49d3-8993-2548e0928471.png)

# Previous firmware

R4b: Internal device features:
- Turn on/off backlight by pressing FPV + MTRS 
- Set backlight brightness level by pressing  FPV and turning BARO encoder
- SPAD Snippet EFIS #6486 or "Core Flight Technologies PMDG 737 EFIS Panel complete device (testing)"

CFT_737_EFIS_PANEL_SPAD_1L2P_R07:
"r07 SPAD 0.9.13.7 update, backlight auto turn OFF on 300s SPAD no ping timeout"

CFT_737_EFIS_PANEL_SPAD_1L2P_R04b:
"Official VIP PID registration, State scan feature is now enabled, new VIRTUAL_POWER variable is available."

CFT_737_EFIS_PANEL_SPAD_1L2P_R04:
"Official VIP PID registration, State scan feature is now enabled, new VIRTUAL_POWER variable is available."

CFT_737_EFIS_PANEL_SPAD_1L2P_R02c_20221022_1553
"Soft reset by pressing FPV and MTRS should not be needed anymore after a cold reboot of the EFIS device. Not a very academic fix, but it looks ok." @1L2P
- Turn on/off backlight by pressing FPV + MTRS 
- Set backlight brightness level by pressing  FPV and turning BARO encoder

CFT_737_EFIS_PANEL_SPAD_1L2P_R02b_20221014_1410:
"The EFIS panel may not be fully initialized when rebooting the PC or after reconnecting it to an USB port. Everything seems to be fine but serial COMs are in a strange state.
As workaround you may have to soft reset the EFIS panel by pressing FPV and MTRS buttons at the same time. The backlight should blink 5 times.
You will have to perform this soft reset only once before starting SPAD, but every time the PC or the EFIS Panel are restarted.
Then when SPAD is started, and if the panel is fully ok, pressing both buttons will only turn ON and OFF the backlight without resetting it."
