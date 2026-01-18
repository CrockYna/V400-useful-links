# V400-useful-links
Useful website with lot of interesting details: https://ellis3dp.com/Print-Tuning-Guide/ <p>
Simple repo containing links useful for printing with FLSUN V400, got from anywhere on the web<p>
Hotend change: https://www.lesimprimantes3d.fr/forum/topic/49962-flsun-v400-hotend-upgrade-trianglelab-chc-pro-bondtech-cht-volcano/ <p>
Printer board: (mine is a nano v2.1 with GD32F303, which is a clone of MKS robin nano v2. I assume the board schema is almost the same.): https://github.com/makerbase-mks/MKS-Robin-Nano-V2.X/wiki/Wiring_Pinout_and_Size <p> 
Speeder pad wifi antenna mod: https://www.lesimprimantes3d.fr/forum/topic/49878-flsun-v400-speeder-pad-am%C3%A9lioration-du-wi-fi-antenne-externe/ <p>
NeoPixel: https://cdn-learn.adafruit.com/downloads/pdf/adafruit-neopixel-uberguide.pdf <p>
Klipper useful macros: https://github.com/rootiest/zippy_guides/tree/main <p>

# Air filtering
* A good filter, originally for Voron printers: https://github.com/nevermore3d/Nevermore_Micro <p>
* Piloting exhaust fan with Klipper: https://github.com/top-gun/Nevermore-Klipper/tree/main <p>
* Air filter Klipper macros: https://github.com/MapleLeafMakers/KlipperMacros/tree/main <p>
* About enclosures: https://howto3dprint.net/the-ultimate-guide-to-3d-printer-enclosures/ <p>
About particle emission in 3D printing:<p>
* https://all3dp.com/1/3d-printing-emissions-air-quality/ <p>
* https://howto3dprint.net/3d-printer-fumes/#hepa-high-efficiency-particulate-air-filters <p>
Sensor that can detect PM0.1 particles (ultra fine particles starting at 0.1um and below: this is the range where 3D printing emits...): <p>
* IPS-7100: buying and documentation: https://fr.farnell.com/piera-systems/ips-7100-1/capteur-particule-air-5-5v/dp/4015788?pf_custSiteRedirect=true <p>
* Arduino code: https://github.com/PieraSystems/7100-I2C-example <p>
Can be useful to look at: <p>
* Simple VOC emission monitor: [https://hackaday.io/project/167424/instructions](https://hackaday.io/project/167424-smart-3d-printer-emission-monitor)https://hackaday.io/project/167424-smart-3d-printer-emission-monitor <p>

# RP2040 RPI PICO board (for adxl and sensors)
* https://github.com/EiNSTeiN-/klipper-rp2040-gpio-board <p>
* https://www.waveshare.com/wiki/RP2040-Zero#Open_Source_Demo <p>

# Getting sensors output on Klipper, with RP2040 RPI PICO
* https://github.com/Villiem/klipper_i2c <p>
* https://github.com/Rappetor/Sovol-SV08-Mainline/tree/main/pico-thermistor <p>

# Sensors programming
* BMP/BME 280: https://circuitdigest.com/microcontroller-projects/interfacing-bmp280-sensor-with-arduino <p>
* Gas sensor MICS5524: https://wiki.dfrobot.com/Fermion__MEMS_Gas_Sensor___MiCS-5524_SKU_SEN0440 <p>
* CCS811: https://cdn.sparkfun.com/assets/2/c/c/6/5/CN04-2019_attachment_CCS811_Datasheet_v1-06.pdf ; https://github.com/maarten-pennings/CCS811 ; https://wiki.dfrobot.com/CCS811_Air_Quality_Sensor_SKU_SEN0339 <p>
* PMS5003: https://cdn-shop.adafruit.com/product-files/3686/plantower-pms5003-manual_v2-3.pdf <p>
* Air Quality sensor + box: https://github.com/SuperHouse/AQS/tree/main?tab=readme-ov-file <p>

# Cam
* ESP32-Cam programming: https://github.com/easytarget/esp32-cam-webserver <p>
