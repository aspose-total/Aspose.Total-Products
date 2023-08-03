---
title: การแปลงรูปแบบไฟล์ผ่าน PHP 

description: แปลงรูปแบบ Microsoft Excel และ PowerPoint เป็นรูปแบบยอดนิยมอื่น ๆ รวมทั้ง PDF, HTML และรูปภาพด้วยโค้ดเพียงไม่กี่บรรทัด
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="การแปลงรูปแบบไฟล์โดยใช้ PHP" h2="แปลง Microsoft<sup>&reg;</sup> สไลด์ Office Excel และ PowerPoint เป็นรูปแบบอื่นๆ รวมถึงรูปภาพ, HTML และ PDF โดยไม่ต้องใช้ซอฟต์แวร์อื่นใด" >}}

{{% blocks/products/pf/feature-page-summary %}}
[PHP รวมไลบรารี](https://products.aspose.com/total/php-java/) เพิ่มความเร็วในการพัฒนาโซลูชันการจัดการเอกสารโดยเฉพาะเอกสาร Excel และ PowerPoint ตั้งแต่เริ่มต้นหรือปรับปรุงแอปพลิเคชันที่มีอยู่เพื่อจัดการกับการจัดการเอกสารได้อย่างง่ายดาย API ไม่เพียงแต่จัดการเอกสาร Microsoft Powerpoint และ Excel แต่ยังแปลงไฟล์ PDF, HTML, รูปภาพ TIFF, JPG, PNG, BMP เป็นชุดที่สมบูรณ์ของการจัดการเอกสาร Excel และ Powerpoint และ API โซลูชันการจัดการโดยไม่ต้องพึ่งพาซอฟต์แวร์ใดๆ  โปรแกรมเมอร์สามารถจัดการและแปลงเอกสาร Excel และ Powerpoint ระหว่างรูปแบบที่นิยมมากที่สุดในแอปพลิเคชันที่ใช้ PHP ได้อย่างง่ายดาย

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="แปลง Excel เป็น HTML" %}}
Total API รองรับการแปลงระหว่างรูปแบบ Microsoft Excel รวมทั้งสามารถแปลง Excel เป็น PDF, HTML และรูปภาพ ขั้นตอนการแปลงเป็นเรื่องง่าย  นำเข้าไลบรารีที่จำเป็นสำหรับ Aspose.Cells และ Java Bridge ไลบรารีเหล่านี้จะใช้เพื่อเข้าถึงสมุดงาน Excel และจัดการการแปลง สร้างอินสแตนซ์ใหม่ของคลาสสมุดงาน โดยแสดงสมุดงาน Excel ที่คุณต้องการแปลง เพียงเรียกใช้เมธอด Save ด้วยรูปแบบเป้าหมายและการแจงนับ SaveFormat เป็นพารามิเตอร์ มันง่ายมาก 

{{% blocks/products/pf/feature-page-code h3="PHP - การแปลง Excel เป็น HTML" %}}

{{< gist "aspose-com-gists" "8e9ad83326cfb7c5b163348006171785" "convert-excel-to-html.php" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="excel-to-powerpoint xlsx-to-pptx xls-to-ppt" >}}


{{% blocks/products/pf/feature-page-section  h2="แปลง Powerpoint เป็นรูปภาพ" %}}
API รองรับการแปลงสไลด์ Popwerpoint เป็นภาพ JPEG, PNG, BMP, TIFF และ GIF สำหรับการแปลงภาพเป็น presnetation ให้พิจารณาภาพ JPG เป็นไฟล์เป้าหมาย ขั้นตอนคือนำเข้าไลบรารีที่จำเป็นสำหรับ Aspose.Slides และ Java Bridge ไลบรารีเหล่านี้จะใช้เพื่อเข้าถึงงานนำเสนอและจัดการการแปลง สร้างตัวอย่างใหม่ของคลาสงานนำเสนอ ซึ่งเป็นตัวแทนของงานนำเสนอ PowerPoint ที่คุณต้องการแปลง  จากนั้นดำเนินการวนซ้ำเพื่อวนซ้ำผ่านแต่ละสไลด์ของงานนำเสนอที่โหลดแล้วแปลงเป็นรูปภาพ สุดท้าย ตรวจสอบให้แน่ใจว่ามีการล้างข้อมูลอย่างเหมาะสมโดยการกำจัดวัตถุนำเสนอเพื่อปล่อยทรัพยากร
{{% blocks/products/pf/feature-page-code h3="PHP - การนำเสนอเป็นการแปลงรูปภาพ" %}}

{{< gist "aspose-com-gists" "8e9ad83326cfb7c5b163348006171785" "convert-powerpoint-to-images.php" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}