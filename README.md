# TriBLE_恢復原廠設定(restore_steps)
方法一： 單獨用USB線將TriBLE母板以USB模式連上PC電腦 (一般流程)。 <br> 
方法二： 搭配J-Link裝置與USB線，將TriBLE母板以USB模式連上PC電腦 (完全死機流程)。 <br> 
--------------------------------------------------------------<br> 
**方法一**
* I. 在Arduino IDE選單上，點選 `工具 > 開發板 > Yutech TriAnswer Boards (nRF52 Series) > Yutech TriBLE nRF52840`
* II. 點選 `工具 > 序列埠 > COMXX (Yutech TriBLE nRF52840)`
* III. 點選 `工具 > 燒錄器 > TriBLE Official Firmware`
* IV. 點選 `工具 > 燒錄 Bootloader`
* (電腦設定不同，首次燒錄可能會找不到COM，再從步驟II開始重點一次即可解決問題。)
* V. 等待約 20~30 秒，出現下圖即燒錄成功。
* **Figure of successful burning**<br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/TriBLE_burn_firmware_success.PNG" align="middle"
    alt="Yutech logo" width="500" height=""></code>


**方法二**
* I. 在使用J-Link燒錄之前，請安裝相關驅動程式。 [**點此.**](https://www.segger.com/downloads/jlink/)
* II. 選擇對應作業程式，下載驅動程式。 <br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/JLink_web.png" align="middle"
    alt="Yutech logo" width="1000" height=""></code>
* III. 安裝下載好的驅動程式。 <br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/JLink_install.png" align="middle"
    alt="Yutech logo" width="500" height=""></code>
* IV. 依照下圖，將TriBLE和J-Link裝置組合後，連上電腦。 <br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/readme_12.png" align="middle"
    alt="Yutech logo" width="500" height=""></code>
* V. 開啟 Arduino IDE 程式。
* VI. 在Arduino IDE選單上，點選 `工具 > 開發板 > Yutech TriAnswer Boards (nRF52 Series) > Yutech TriBLE nRF52840`
* VII. 點選 `工具 > 序列埠 > COMXX (Yutech TriBLE nRF52840)`
* VIII. 點選 `工具 > 燒錄器 > TriBLE Official Firmware`
* IX. 點選 `工具 > 燒錄 Bootloader` 並點選 `接受` <br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/readme_13.png" align="middle"
    alt="Yutech logo" width="500" height=""></code>
* X. 等待約 20~30 秒，出現下圖即燒錄成功。
* **Figure of successful burning** <br> <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/readme_14.png" align="middle"
    alt="Yutech logo" width="500" height=""></code>
