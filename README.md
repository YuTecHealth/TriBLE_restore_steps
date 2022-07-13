# TriBLE_restore_steps
#### **Appendix. If you got some trouble... try to renew bootloader!!!!**
Method 1: Connect TriBLE board to PC through USB cable only. <br> 
Method 2: Connect TriBLE board to PC through both J-Link device and USB cable. (Fatal error only) <br> 
--------------------------------------------------------------<br> 
**Method 1**
* I. Select `Tools > Board > Yutech TriAnswer Boards (nRF52 Series) > Yutech TriBLE nRF52840`
* II. Select `Tools > Port > COMXX (Yutech TriBLE nRF52840)`
* III. Select `Tools > Programmer > DFU for TriBLE nRF52`
* IV. Select `Tools > Burn Bootloader`
* V. Wait about 20~30 sec.
* **Figure of successful burning**<br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/readme_14.png" align="middle"
    alt="Yutech logo" width="500" height=""></code>


**Method 2**
* I. To use J-Link, user should install the driver [**Here.**](https://www.segger.com/downloads/jlink/)
* II. Choose your OS and click to download. <br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/JLink_web.png" align="middle"
    alt="Yutech logo" width="1000" height=""></code>
* III. Install the driver. <br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/JLink_install.png" align="middle"
    alt="Yutech logo" width="500" height=""></code>
* IV. Connect TriBLE and J-link to your PC. <br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/readme_12.png" align="middle"
    alt="Yutech logo" width="500" height=""></code>
* V. Launch Arduino IDE.
* VI. Select `Tools > Board > Yutech TriAnswer Boards (nRF52 Series) > Yutech TriBLE nRF52840`
* VII. Select `Tools > Port > COMXX (Yutech TriBLE nRF52840)`
* VIII. Select `Tools > Programmer > J-link for TriBLE nRF52`
* IX. Select `Tools > Burn Bootloader` and press `Accept` <br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/readme_13.png" align="middle"
    alt="Yutech logo" width="500" height=""></code>
* X. Wait about 20~30 sec. 
* **Figure of successful burning** <br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/readme_14.png" align="middle"
    alt="Yutech logo" width="500" height=""></code>
