---
title: แปลงรูปแบบ JSON เป็น OTT ผ่าน Java
description: แยก JSON เป็น OTT ใน Java โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/json-to-ott/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: OTT
otherformats: DOC WORD MOBI RTF DOCM EPUB ODT OTT PS WORDML DOT PCL FLATOPC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น OTT ผ่าน Java" h2="Java API ในตัวเพื่อแยก JSON เป็น OTT โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถแปลง JSON เป็น OTT ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น PDF ในขั้นตอนที่ 2 คุณสามารถแปลง PDF เป็น OTT โดยใช้ Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น OTT ผ่าน Java" %}}
1. สร้าง [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. นำเข้าไฟล์ JSON ไปยังเวิร์กชีตโดยใช้คลาส [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) และ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) เป็น PDF
3. โหลดเอกสาร PDF โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ OTT โดยใช้ [บันทึก](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
นอกจากนี้ API ยังให้คุณตั้งค่าตัวเลือกเลย์เอาต์สำหรับ JSON ของคุณในขณะที่แยกวิเคราะห์ JSON เป็น OTT โดยใช้ [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่า null ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น OTT ผ่าน Java" %}}
เมื่อใช้ API คุณสามารถแยก JSON เป็น OTT ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร OTT ของคุณ ก่อนอื่นให้แปลงไฟล์ JSON เป็น PDF และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PDF ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติของมัน วิธี Call Watermark.setText และส่งข้อความลายน้ำ & วัตถุของ TextWatermarkOptions หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปที่ OTT 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น OTT** เป็นสิ่งจำเป็นสำหรับการสร้าง **เทมเพลตเอกสารข้อความ** จากชุดข้อมูลที่มีโครงสร้าง รูปแบบ OTT, หรือ OpenDocument Text Template, ให้วิธีมาตรฐานในการสร้างเทมเพลตที่สามารถใช้ซ้ำและแก้ไขได้ในชุดโปรแกรมสำนักงานโอเพนซอร์ส เช่น LibreOffice และ OpenOffice โดยการแปลง JSON เป็น OTT องค์กรจะมั่นใจในความสอดคล้อง ความปฏิบัติ และการอัตโนมัติในการสร้างเอกสารในกระบวนการทำงานหลายๆ กระบวนการ

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}

- **กรอบเอกสารของรัฐบาล** – สร้างแบบฟอร์มและรายงานมาตรฐานสำหรับการใช้งานทางการ
- **เทมเพลตทางกฎหมาย** – อัตโนมัติสัญญา ข้อตกลง และรูปแบบที่พร้อมที่จะปฏิบัติตามกฎ
- **จดหมายธุรกิจ** – รักษาความสอดคล้องในการตอบกลับขององค์กร
- **รายงานการศึกษา** – สร้างเทมเพลตเอกสารที่พร้อมใช้งานสำหรับงานวิจัยและการมอบหมาย
- **การผสานรวมกับสำนักงานโอเพนซอร์ส** – ใช้เทมเพลตที่เป็น JSON ได้โดยไม่มีข้อบกพร่องในสภาพแวดล้อมโอเพนซอร์ส

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การอัตโนมัติ" %}}

- **กระแสงาน JSON เป็น OTT** – อัตโนมัติการสร้างเทมเพลตจากชุดข้อมูล JSON ที่มีโครงสร้าง
- **กระบวนการทำงานเทมเพลตอัตโนมัติ** – ลดความพยายามในการจัดรูปแบบด้วยมือข้างหนึ่งข้างอีกข้างของแผนก
- **การสร้างเอกสารด้วย JSON** – บังคับความสอดคล้องในการรายงานขององค์กรและการปฏิบัติตามกฎ
- **การกระจายเทมเพลตขององค์กร** – มาตรฐานเทมเพลตเอกสารในทีมทั่วโลก

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}