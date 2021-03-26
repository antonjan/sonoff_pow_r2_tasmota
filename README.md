# sonoff_pow_r2_tasmota
Pres botton on Sonoff POWR2 when Connecting to device in programer to put device in programming mode.<br>
This Repository will have all the details of the Tasmota Sonoff Pow R2 power meter linked to MQTT<br>
![Programming Cable](sonoff_pow_r2_tasmota_programming_cable_2.jpg?raw=true "Programming Cable")<br>
# Reading the exsiting Sonoff POW R@ file for backup
esptool.py read_flash 0x00000 0x100000 fwbackup.bin
# tasmotize the Sonoff POW R2
/home/anton/anaconda3/bin/tasmotizer.py<br>
Download the bin file from Tasmota for Sonoff<br>
Create config template for Sonnof POW R2<br>

