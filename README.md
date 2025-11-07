#Legal Disclaimer:
USER BEWARE. This is a simple breakout board created as an aid for my own prototyping purposes. 
Not withstanding the preceding and the above, DOWNLOAD, OR USE **SOLELY AT YOUR OWN RISK**. 
No warranty or representation is offered, nor should any be implied, of any kind, whatsoever. 
It is the end user's responsibility to determine suitability for their needs, and it is the end user's responsibility to test accordingly. 
Be sure to comply with all applicable rules and regulations that may govern its possession or use, which may vary by country. 
No recommendation is being made that you use it. No assistance is promised, nor should any assistance be assumed. 
No updates or corrections are promised, nor should any updates or corrections be assumed.

# G-NiceRF LoRa1280F27 Breakout Board

This is an open-source breakout board for the **G-NiceRF LoRa1280F27** 500mW 2.4GHz LoRa module. Please note that this breakout board is not for the  Lora1280F27-TCXO variant which is also produced by G-Nice RF.

## Features
I have Breaken out all 18 pins from the module to standard 2.54mm headers and included two decoupling capacitors (10uF and 100nF) near VCC for stable operation.
I also  did a  **50-ohm coplanar waveguide** trace for the antenna and has inlcuded footprint for a standard **U.FL connector** for easily connecting the antennas.
The module has a full ground plane on both the top and bottom layers with stitching vias for low noise .

## How to Use

* **For KiCad Users:** The full KiCad 9 project is in the `GNice-RF SX1280 F27 Project Files` folder. You must also add the libraries from the `Custom footprint and symbol` folder to your KiCad global libraries.
* **For Manufacturing:** A `.zip` file is in the `GNiceRF SX1280 Gerbers for Fab` folder. You can upload this file directly to any PCB manufacturer.

For pinout, refer to the official G-NiceRF LoRa1280F27 datasheet.
<img width="711" height="842" alt="image" src="https://github.com/user-attachments/assets/cf0d3281-a41a-4d17-9663-2ae6d42b2808" />

For more information ragarding the module, you can refer to the the datasheet: https://www.nicerf.com/lora-module/sx1280-lora-module-lora1280f27.html

