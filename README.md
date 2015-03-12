# sleepytypetool
Exported from http://code.google.com/p/sleepytypetool

Donate
---
  * more money = more free time = more free code!
  * บริจาคเงินให้ผู้จัดทำ = คนทำมีเวลาว่าง = มีโปรแกรมฟรีมาให้ใช้เรื่อยๆ
[กดเพื่อบริจาค](https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=katopz%40gmail%2ecom&lc=TH&item_name=sleepytypetool&item_number=sleepytypetool&button_subtype=services&no_note=0&currency_code=USD&bn=PP%2dBuyNowBF%3abtn_buynowCC_LG%2egif%3aNonHostedGues) 

Tools
---
  * online : http://sleepydesign.com/services/typetool/
  * offline : wait for donation.

Feature
---
  * แก้สระลอย, จัดตำแหน่งตำแหน่งสระ/วรรณยุกต์ ที่ลอย หรือทับหาง (AS2, AS3)
  * แก้ไขปัญหาการแสดงผล ญ ในโปรแกรม Adobe Photoshop 7
  * แก้ไขปัญหาภาษาไทยพิมพ์ไม่ได้ในโปรแกรม Adobe CS, CS2, CS3, CS4, CS5, CS5.5, CS6, CS7, CC, CC 2014
  * สร้าง embed font สำหรับ Adobe Flash
  * ตัวปัดบรรทัด(0x0D0A)ตัด Carriage Return(0x0D)+ Line Feed(0x0A) เหลือแค่ (0x0A)
  * ยกเลิกการแก้ไขจากตัวที่แก้ (fix)ไปแล้ว (AS2, AS3)
   
To do
---
  * Clean up code
  * for each/bitwise optimize
  * RegEXP
  * AIR application (รอคนบริจาคเงินก่อน -..-)

Target
---
```
อ่อ้อ๊อ๋อ์อํอ็ป่ป้ป๊ป๋ป์ปํป็อั่อั้อั๊อั๋ปั่ปั้ปั๊ปั๋อิ่อี้อึ๊อื๋ปิ่ปี้ปึ๊ปื๋ปิ์อำอ่ำอ้ำอ๊ำอ๋ำปำป่ำป้ำป๊ำป๋ำปุ่ปุ้ปุ๊ปุ๋อุอูอฺญญุญูญฺฤุฤูฤฺฎุฎูฎฺฏุฏูฏฺฐฐุฐูฐฺ
```

Font Support
---
  * PSL-AD, DB-, JS-, Courier
  * PSL, PSL-SP, NP, UPC, DSE, Tahoma, TH(SIPA)
  * DS-

Output
---
  * Unicode(Multibyte)/Ascii for Adobe Flash, Photoshop, Illustrator, Xara, etc.

Examples (for runtime)
---
```actionscript
textField.text = ThaiUtil.fix("ก่า");
```
