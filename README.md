ESP32-NODEMCU WiFi Jammer


อุปรณ์รบกวนสัญญาณ Bluetooth,WiFi,CCTV และอื่นๆที่อยู่ในคลื่นความถี่ 2.4Ghz


วิธี Flash ลงบอร์ด


1.โหลดไฟล์ jammer.bin


2.ไปที่เว็บ https://espressif.github.io/esptool-js


 3.!!ระหว่างขั้นตอนนี้กดปุ่ม BOOT บน ESP32 ค้างไว้ตลอด!! > กด Connect (Baudrate 115200) > เลือก COM (พอร์ต) ของ ESP32 > เลือกไฟล์ jammer.ino.merged.bin > Flash Address ใส่ 0x0 > กด Program และรอจนแฟลชเสร็จ


 4.กดปุ่ม RST 1 ครั้งบนบอร์ด , ไม่ก็ถอดเสียบ ESP32 ใหม่


วิธีใช้งาน


เชื่อมต่อ WiFi ที่ชื่อ "MarkTV" รหัสผ่าน "admin1234"


แล้วเข้าไปที่เว็บ "192.168.1.67"

![daab86d8-4e1c-4bbc-9f9c-0cb122080f9e](https://github.com/user-attachments/assets/13db2ec7-7399-4359-a7d1-f8caa7e35b17) ![a83d5797-57be-4656-9c80-76385ddf655a](https://github.com/user-attachments/assets/d06040d1-8803-4e6f-90ee-7d8b33fd386d)
