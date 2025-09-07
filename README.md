# PS5 Auto Jailbreak and Auto Run Payload
**Auto Jailbreaks and Load autorun.bin or autorun.elf once the jailbreak is done for ESP32-S3 (16MB) boards. Based on [idlesauce UTMX2](https://github.com/idlesauce/umtx2) with an admin file manager. Supports PS5 firmware 1.00-5.50**

Board Link Sample: [Aliexpress](https://www.aliexpress.com/item/1005009169425759.html?spm=a2g0o.order_list.order_list_main.5.7c081802iYkPup)

<img width="352" height="196" alt="image" src="https://github.com/user-attachments/assets/b5817a26-9b0c-481f-8599-f08c39b4d048" />

**Features:**
- Auto Payload Execution: just upload either "autorun.elf" or "autorun.bin" to be run once the jailbreak is done. (Auto loads etaHEN 2.3b by default as it names as autorun.bin)
- use L1 to show the console log (default is hidden now)
- New File Manager
    - Ability to rename payloads to modify the autorun payloads even from PS5 itself
    - New Icons and Storage Size Bar
- More freed storage ≈15 mb in total
- New Background Animation
- Liquid Glass Buttons 🥛
- More Payloads per row
- Payload description on hover
- Energy Saving & Sleep Mode ♻️: The board will run for 5 minutes then it will enter sleep mode after to save energy and prevent overheating. If you wish to keep the board running, then hold the RESET button for 2 seconds when the green LED light is up until it changes the green LED color 🟢 to 🌈 multi RGB colors cycle. (To wake up the board either press one time on the BOOT button or power cycle it)

**PS5 UTMX2 with the following Payloads included**

<img width="268" height="463" alt="image" src="https://github.com/user-attachments/assets/daa9662b-4d7a-4928-b058-7b5d4f652494" />

**Access the admin page to manage payloads on http://10.1.1.1/admin**

<img width="882" height="680" alt="image" src="https://github.com/user-attachments/assets/c2f2d05a-6904-47e1-ba96-e33cfbdb9c61" />

Youtube Showcase

[![YouTube Showcase](https://img.youtube.com/vi/9uR-GHJIST8/0.jpg)](https://www.youtube.com/watch?v=9uR-GHJIST8?si=aqvrtfWnTFVA_c1n&amp;start=463)

**How to use:**

Use [NodeMCU PyFlasher](https://github.com/marcelstoer/nodemcu-pyflasher/releases) to flash the **AutoJB+AutorunPayload-2.1.bin** file then disconnect/connect the usb to power cycle

<img width="704" height="753" alt="image" src="https://github.com/user-attachments/assets/13c77536-8e1f-4c03-89c8-9722605ff74f" />

Join the Open WIFI Network: "PS5_Auto_Host" with your PS5 and PC for file management

<img width="355" height="203" alt="image" src="https://github.com/user-attachments/assets/d1fefab7-b3c6-42e4-95c1-d0b30478cc9a" />
