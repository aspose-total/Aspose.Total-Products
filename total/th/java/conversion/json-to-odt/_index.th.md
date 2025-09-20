---
title: แปลงรูปแบบ JSON เป็น ODT ผ่าน Java
description: แยก JSON เป็น ODT ใน Java โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/json-to-odt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODT
otherformats: WORDML EPUB WORD RTF DOT ODT PCL PS DOCM DOC OTT MOBI FLATOPC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น ODT ผ่าน Java" h2="Java API ในตัวเพื่อแยก JSON เป็น ODT โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถแปลง JSON เป็น ODT ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น PDF ในขั้นตอนที่ 2 คุณสามารถแปลง PDF เป็น ODT โดยใช้ Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น ODT ผ่าน Java" %}}
1. สร้าง [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. นำเข้าไฟล์ JSON ไปยังเวิร์กชีตโดยใช้คลาส [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) และ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) เป็น PDF
3. โหลดเอกสาร PDF โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ ODT โดยใช้ [บันทึก](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) กระบวนการ
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
นอกจากนี้ API ยังให้คุณตั้งค่าตัวเลือกเลย์เอาต์สำหรับ JSON ของคุณในขณะที่แยกวิเคราะห์ JSON เป็น ODT โดยใช้ [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่า null ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น ODT ผ่าน Java" %}}
เมื่อใช้ API คุณสามารถแยก JSON เป็น ODT ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร ODT ของคุณ ก่อนอื่นให้แปลงไฟล์ JSON เป็น PDF และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PDF ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติของมัน วิธี Call Watermark.setText และส่งข้อความลายน้ำ & วัตถุของ TextWatermarkOptions หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปที่ ODT 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น ODT** เป็นสิ่งจำเป็นสำหรับการสร้าง **ไฟล์ข้อความ OpenDocument** จากชุดข้อมูลที่มีโครงสร้าง ไฟล์ ODT ซึ่งเป็นรูปแบบเดิมสำหรับ LibreOffice และ OpenOffice ช่วยให้สามารถเข้าถึงได้ในระยะยาว มีความเข้ากันได้กับโอเพนซอร์ส และสามารถใช้งานได้บนหลายแพลตฟอร์ม โดยการแปลง JSON เป็น ODT องค์กรสามารถอัตโนมัติสร้างเอกสารข้อความที่มีความเชื่อถือจากข้อมูลโดยไม่ต้องแก้ไขด้วยมือ

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}

- **เอกสารของรัฐบาล** – สร้างเอกสารที่เป็นไปตามข้อกำหนดและมาตรฐานสำหรับการบริหารราชการ
- **กระบวนการทำงานสำนักงานโอเพนซอร์ส** – ผสานข้อมูล JSON กับสภาพแวดล้อม LibreOffice และ Apache OpenOffice
- **เอกสารทางวิชาการ** – สร้างรายงานวิจัยและการตีพิมพ์จากชุดข้อมูลที่มีโครงสร้าง
- **สัญญาธุรกิจ** – อัตโนมัติการร่างข้อตกลงและสร้างสัญญาจากบันทึก JSON
- **จดหมายที่ขับเคลื่อนด้วยข้อมูล** – สร้างการสื่อสารโครงสร้างที่ปรับให้เหมาะกับบุคคลอย่างมาก

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}

- **ท่อการเปลี่ยน JSON เป็น ODT** – อัตโนมัติการแปลงข้อมูลโครงสร้างเป็นเอกสาร ODT ที่สามารถแก้ไขได้
- **การสร้าง ODT โดยอัตโนมัติ** – ลดความพยายามในการทำด้วยมือโดยการสร้างไฟล์ข้อความที่พร้อมใช้งานโดยตรงจาก JSON
- **มาตรฐานการแปลง JSON เป็น OpenDocument** – รักษาความเป็นไปตามมาตรฐานเปิดสำหรับการแชร์เอกสาร
- **กระบวนการทำงานเอกสารข้ามแพลตฟอร์ม** – เปิดให้ใช้งานได้อย่างเรียบร้อยในระบบองค์กรและทางวิชาการ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}