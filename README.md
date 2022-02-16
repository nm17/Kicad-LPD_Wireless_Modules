# KiCad-LPD\_Wireless\_Modules
Wireless transmitter & receiver modules Symbol and Footprint repo for KiCad (also includes eval boards for development use)

### What is this repo for?
This repository contains symbols and footprints for various cheap LPD (low power device) radio modules for transmitting and receiving of signals on the 433/868/915 MHz frequency. These modules are meant for use in other systems via soldering onboard, hence the need for a library that provides definitions of these modules for use in programs like KiCad. By making the footprints and symbols available, it makes it easier for others to develop and prototype boards using these modules.

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/nm17/Kicad-LPD_Wireless_Modules">LPD Wireless Module Kicad Library</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/nm17">nm17</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p> 

## How to use

  1. Clone this repository or download and unpack the zip file either from master or releases.
  2. Add the symbol and footprint library from `KiCad -> Preferences -> Manage Symbol libraries...` and `KiCad -> Preferences -> Manage Footprint libraries...`
  3. Check if new `LPD_Wireless_Modules` category appears.

## Symbols & Footprints available

  - **VT-CC1120PL** based boards: RF module based on TI CC1120 transceiver
	  + AliExpress: https://www.aliexpress.com/item/32828042198.html
  - **CC1120 + CC1190PA** module (also known as CC1120PATR8-KRD PCB v3.0): RF module based on TI CC1120 + CC1190PA transceivers
	  + AliExpress: https://www.aliexpress.com/item/1005001309489904.html
  - Generic **QLP20** footprint: Used for CC1120-like IC's
  - **VT-DTMSX3** board: RF Module based on CC1120 transceiver and Cortex-M3 chip that provides wireless **UART** connectivity
	  + AliExpress: https://www.aliexpress.com/item/32932216351.html
  - **RFM69** board: A highly integrated RF transceiver capable of operation over a wide frequency range by HopeRF electronics.
	  + AliExpress: https://www.aliexpress.com/item/32827496282.html
