---
title: แปลงรูปแบบ JSON เป็น FLATOPC ผ่าน Java
description: แยก JSON เป็น FLATOPC ใน Java โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/json-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: FLATOPC
otherformats: EPUB ODT PCL WORD RTF DOC DOCM DOTX DOT MOBI PS FLATOPC WORDML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น FLATOPC ผ่าน Java" h2="Java API ในตัวเพื่อแยก JSON เป็น FLATOPC โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถแปลง JSON เป็น FLATOPC ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น PDF ในขั้นตอนที่ 2 คุณสามารถแปลง PDF เป็น FLATOPC โดยใช้ Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น FLATOPC ผ่าน Java" %}}
1. สร้าง [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. นำเข้าไฟล์ JSON ไปยังเวิร์กชีตโดยใช้คลาส [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) และ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) เป็น PDF
3. โหลดเอกสาร PDF โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ FLATOPC โดยใช้ [บันทึก](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) กระบวนการ
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
นอกจากนี้ API ยังให้คุณตั้งค่าตัวเลือกเลย์เอาต์สำหรับ JSON ของคุณในขณะที่แยกวิเคราะห์ JSON เป็น FLATOPC โดยใช้ [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่า null ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น FLATOPC ผ่าน Java" %}}
เมื่อใช้ API คุณสามารถแยก JSON เป็น FLATOPC ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร FLATOPC ของคุณ ก่อนอื่นให้แปลงไฟล์ JSON เป็น PDF และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PDF ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติของมัน วิธี Call Watermark.setText และส่งข้อความลายน้ำ & วัตถุของ TextWatermarkOptions หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปที่ FLATOPC 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น FLATOPC** เป็นสิ่งจำเป็นสำหรับการแปลง **ข้อมูลโครงสร้างเป็นรูปแบบ Word ในรูปแบบ OpenXML**  FLATOPC ให้การแสดงข้อมูลแบบ XML ที่มีมาตรฐานของเอกสาร Word ทำให้เหมาะสำหรับการแลกเปลี่ยนข้อมูล การถ่ายเท และการทำงานอัตโนมัติ โดยการแปลง JSON เป็น FLATOPC องค์กรสามารถเชื่อมต่อชุดข้อมูลโครงสร้างกับ WordprocessingML ทำให้สามารถใช้งานร่วมกันได้อย่างไม่มีข้อบกพร่อง การปฏิบัติตามข้อบังคับ และการสร้างเอกสารระดับองค์กรได้

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}

- **เอกสารถาวร** – รักษาข้อมูลโครงสร้างในรูปแบบ Word ที่ใช้ XML ในระยะยาว
- **กระบวนการทำงานขององค์กร** – ผสานเนื้อหาที่ใช้ JSON เข้ากับระบบเอกสารของบริษัท
- **ความสามารถในการทำงานร่วมกันระหว่างระบบ** – แลกเปลี่ยนเนื้อหา Word ที่มีมาตรฐานในแอปพลิเคชัน
- **กรอบกฎหมาย** – สร้างเอกสาร Word ที่พร้อมที่จะปฏิบัติตามจากแหล่งข้อมูลโครงสร้าง
- **เนื้อหา Word ที่มีข้อมูลสนับสนุน** – สร้างไฟล์ Word โดยตรงจากชุดข้อมูล JSON ที่มีชีวิตหรือเก็บไว้

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การอัตโนมัติ" %}}

- **ท่อการส่งข้อมูล JSON เป็น FLATOPC** – ทำให้การแปลงชุดข้อมูลโครงสร้างเป็นรูปแบบ Word ใน OpenXML เป็นอัตโนมัติ
- **การเก็บเอกสารอัตโนมัติ** – สร้างเอกสาร Word ที่ใช้ XML โดยตรงจากบันทึก JSON
- **การมาตรฐานการสร้างเอกสารจาก JSON ที่พร้อมใช้งานในคลาวด์** – ทำให้การสร้างเอกสารที่มีมาตรฐานได้ในสภาพแวดล้อมคลาวด์
- **การแปลงเอกสารขนาดใหญ่** – ประมวลผลไฟล์ JSON จำนวนมากเป็น FLATOPC สำหรับระบบเอกสารขององค์กร

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}