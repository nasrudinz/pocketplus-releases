# Pocket+ สำหรับ Galaxy 5G Mobile Wi-Fi SCR01

โปรแกรม Windows สำหรับดูสถานะและเพิ่มความสามารถให้ pocket wifi **Samsung Galaxy 5G Mobile Wi-Fi SCR01** (au, SM-H412J) ผ่านสาย USB
ใช้ฟรี · ภาษาไทย/อังกฤษ · สำรองค่าก่อนแก้ทุกครั้ง

**[⬇ ดาวน์โหลดเวอร์ชันล่าสุด](https://github.com/nasrudinz/pocketplus-releases/releases/latest)** — ไฟล์ `PocketPlus_x.y.z_x64-setup.exe`

## ทำอะไรได้บ้าง

- **ภาพรวม / เครือข่าย** — สัญญาณ LTE/5G, band, แบต, อุณหภูมิ, เน็ตที่ใช้ไป อัปเดตทุก 10 วินาที
- **Express 5G ไทย** — ตรวจว่าเครื่องพร้อมใช้ 5G กับซิมไทยไหม และแก้ Allow list / SA-NSA ใน ServiceMode ให้ (ยืนยันก่อนทุกครั้ง)
- **เพิ่มความสามารถ** — เปลี่ยน launcher, ติดตั้งคีย์บอร์ดไทย, ติดตั้งแอปจาก F-Droid หรือไฟล์ APK (ตรวจลายเซ็นก่อน)
- **สำรองและกู้คืน** — สำรองค่าเครื่องลงคอม เทียบ และคืนค่า
- **เครื่องมือ** — เปิดจอเครื่องบนคอม, หาจุดวางเครื่องที่สัญญาณดีสุด, ต่อสัญญาณใหม่, ตรวจสภาพเครื่อง (เคย root ไหม ฮาร์ดแวร์ไหนใช้ได้จริง)
- **แจ้งเตือน** — เครื่องร้อน, เน็ตใกล้หมด, เครื่องหลุด · อัปเดตตัวเองได้

## เริ่มใช้งาน

1. ติดตั้ง `PocketPlus_…_x64-setup.exe` (Windows 10/11, 64-bit)
   Windows อาจขึ้น "Windows protected your PC" เพราะยังไม่ได้ซื้อใบรับรองเซ็นโปรแกรม → **More info › Run anyway**
2. บน SCR01 เปิด USB debugging: เมนู › About › Status › แตะ IMEI 10 ครั้ง (ดูคู่มือในโปรแกรม)
3. เสียบสาย USB แล้วกด Allow บนเครื่อง
4. ถ้าคอมยังไม่มี adb โปรแกรมจะขออนุญาตดาวน์โหลด platform-tools จาก Google ให้

ตรวจไฟล์ได้จาก `SHA256SUMS.txt` ในแต่ละ release · อัปเดตผ่านโปรแกรมจะติดตั้งเฉพาะไฟล์ที่เซ็นด้วยกุญแจของ Pocket+

## ข้อควรรู้

- ทุกการแก้ค่าในเครื่อง (ServiceMode, หน้า Home, คีย์บอร์ด, ติดตั้ง/ลบแอป) ต้องกดยืนยัน และสำรองค่าก่อนเสมอ
- Pocket+ ไม่แนบ adb หรือแอปของคนอื่นมาในตัวติดตั้ง
- ฮาร์ดแวร์ของ SCR01 ที่ใช้ไม่ได้: Bluetooth (ปิดจากเฟิร์มแวร์), GPS, กล้อง, ลำโพง · Play Store ใช้ไม่ได้ถ้าไม่ root (ใช้ Aurora Store แทน)
- ปุ่ม Home บนจอของ SCR01 จะเปิดหน้าเราเตอร์เสมอ — ใช้ปุ่ม "เปิดตอนนี้" หรือ One Hand Operation + เพื่อเรียก launcher

## แจ้งปัญหา / สนับสนุน

- แจ้งปัญหาหรือเสนอไอเดียที่ [Issues](https://github.com/nasrudinz/pocketplus-releases/issues)
- ถ้าโปรแกรมช่วยคุณได้ เลี้ยงกาแฟผู้พัฒนาได้ที่ **[buymeacoffee.com/nasrudinz](https://buymeacoffee.com/nasrudinz)** ☕

---

## English

**Pocket+** is a free Windows app for the **Samsung Galaxy 5G Mobile Wi-Fi SCR01** (au, SM-H412J). Over USB/ADB it shows live signal, battery and data use, checks and fixes 5G settings for Thai SIMs (ServiceMode allow list, SA/NSA), changes the launcher and keyboard, installs apps from F-Droid or checked APK files, backs up and restores settings, mirrors the screen, checks the device for root/tampering, and updates itself.

**[Download the latest release](https://github.com/nasrudinz/pocketplus-releases/releases/latest)** · Windows 10/11 x64 · Thai and English UI.
Every change on the device is confirmed first and backed up. Windows SmartScreen may warn because the installer is not code-signed: *More info › Run anyway*.

---

Pocket+ is freeware by **nasrudinz**, closed source — see [LICENSE](LICENSE).
**Not affiliated with Samsung, au/KDDI or Google.** "Galaxy" and "Samsung" are trademarks of Samsung Electronics. Changing ServiceMode settings is at your own risk.
