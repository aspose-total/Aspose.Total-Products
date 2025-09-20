---
title: แปลงรูปแบบ JSON เป็น DOC ผ่าน Java
description: แยก JSON เป็น DOC ใน Java โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/json-to-doc/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOC
otherformats: OTT DOTX MOBI DOC DOT DOCM RTF PCL PS ODT EPUB WORDML FLATOPC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น DOC ผ่าน Java" h2="Java API ในตัวเพื่อแยก JSON เป็น DOC โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถแปลง JSON เป็น DOC ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น PDF ในขั้นตอนที่ 2 คุณสามารถแปลง PDF เป็น DOC โดยใช้ Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น DOC ผ่าน Java" %}}
1. สร้าง [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. นำเข้าไฟล์ JSON ไปยังเวิร์กชีตโดยใช้คลาส [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) และ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) เป็น PDF
3. โหลดเอกสาร PDF โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ DOC โดยใช้ [บันทึก](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) กระบวนการ
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
นอกจากนี้ API ยังให้คุณตั้งค่าตัวเลือกเลย์เอาต์สำหรับ JSON ของคุณในขณะที่แยกวิเคราะห์ JSON เป็น DOC โดยใช้ [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่า null ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น DOC ผ่าน Java" %}}
เมื่อใช้ API คุณสามารถแยก JSON เป็น DOC ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร DOC ของคุณ ก่อนอื่นให้แปลงไฟล์ JSON เป็น PDF และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PDF ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติของมัน วิธี Call Watermark.setText และส่งข้อความลายน้ำ & วัตถุของ TextWatermarkOptions หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปที่ DOC 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น DOC** เป็นสิ่งจำเป็นสำหรับการแปลง **ชุดข้อมูลที่มีโครงสร้าง** เป็นเอกสาร Word ที่สามารถแก้ไขได้อย่างเต็มที่ กระบวนการนี้เชื่อมสายข้อมูลดิบกับรูปแบบที่สามารถอ่านได้ของมนุษย์ ทำให้ธุรกิจและองค์กรสามารถสร้างเอกสารที่เรียบร้อย มาตรฐาน และพร้อมให้กับลูกค้าโดยตรงจากเนื้อหา JSON โดยการแปลง JSON เป็นไฟล์ DOC ข้อมูลที่มีโครงสร้างกลายเป็นเนื้อหาที่สามารถเข้าถึงได้สำหรับการแก้ไข การทำงานร่วมกัน และการไหลของงานที่มีการปฏิบัติตามข้อบังคับ

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}

- **รายงานธุรกิจ** – แปลงข้อมูลที่มีรูปแบบ JSON เป็นรายงาน Word อย่างมืออาชีพ
- **เอกสารนโยบาย** – สร้างเอกสารนโยบายและเอกสารกฎหมายที่สามารถแก้ไขได้จากชุดข้อมูล
- **การสร้างเนื้อหาโดยใช้ข้อมูล** – อัตโนมัติการสร้างเอกสารจากข้อมูลที่มีโครงสร้าง
- **บันทึกการปฏิบัติตามข้อบังคับ** – มาตรฐานไฟล์ Word ที่พร้อมใช้งานทางกฎหมายและการตรวจสอบจากแหล่งข้อมูล JSON
- **รายงานที่พร้อมส่งให้กับลูกค้า** – ส่งมอบรายงานที่เรียบร้อยและสามารถแก้ไขได้ โดยใช้ข้อมูลแบบเรียลไทม์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การอัตโนมัติ" %}}

- **ท่อการทำงาน JSON เป็น DOC** – ปรับปรุงกระบวนการแปลงข้อมูลเป็นไฟล์ Word ที่สามารถแก้ไขได้
- **การสร้างรายงานโดยอัตโนมัติ** – สร้างเอกสาร Word โดยไดนามิกจาก JSON feeds
- **กระบวนการทำงานข้อมูลสู่เอกสารขององค์กร** – รวมเนื้อหาที่เป็นไปตาม JSON เข้าสู่ระบบเอกสารขององค์กร
- **มาตรฐานเอกสารจากข้อมูล JSON** – รักษาความสม่ำเสมอและการปฏิบัติตามข้อบังคับในไฟล์ Word ที่สร้างขึ้นทั้งหมด

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}