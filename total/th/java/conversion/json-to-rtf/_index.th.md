---
title: แปลงรูปแบบ JSON เป็น RTF ผ่าน Java
description: แยก JSON เป็น RTF ใน Java โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/json-to-rtf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: RTF
otherformats: EPUB FLATOPC PCL WORDML DOTX PS DOCM RTF DOC WORD MOBI ODT DOT OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น RTF ผ่าน Java" h2="Java API ในตัวเพื่อแยก JSON เป็น RTF โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถแปลง JSON เป็น RTF ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น PDF ในขั้นตอนที่ 2 คุณสามารถแปลง PDF เป็น RTF โดยใช้ Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น RTF ผ่าน Java" %}}
1. สร้าง [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. นำเข้าไฟล์ JSON ไปยังเวิร์กชีตโดยใช้คลาส [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) และ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) เป็น PDF
3. โหลดเอกสาร PDF โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ RTF โดยใช้ [บันทึก](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) กระบวนการ
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
นอกจากนี้ API ยังให้คุณตั้งค่าตัวเลือกเลย์เอาต์สำหรับ JSON ของคุณในขณะที่แยกวิเคราะห์ JSON เป็น RTF โดยใช้ [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่า null ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น RTF ผ่าน Java" %}}
เมื่อใช้ API คุณสามารถแยก JSON เป็น RTF ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร RTF ของคุณ ก่อนอื่นให้แปลงไฟล์ JSON เป็น PDF และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PDF ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติของมัน วิธี Call Watermark.setText และส่งข้อความลายน้ำ & วัตถุของ TextWatermarkOptions หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปที่ RTF 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น RTF** เป็นสิ่งสำคัญสำหรับการสร้าง **เอกสาร Rich Text 跨แพลตฟอร์ม** จากข้อมูลโครงสร้าง ไฟล์ RTF มีความเข้ากันได้กว้างทั้งในระบบปฏิบัติการ เครื่องมือสร้างข้อความ และแพลตฟอร์มโบราณ ทำให้เหมาะสำหรับองค์กรที่ต้องการเอกสารที่มีน้ำหนักเบา พกพาง่าย และมีการจัดรูปแบบ เมื่อแปลง JSON เป็น RTF ธุรกิจสามารถเปิดใช้งานการนำเสนอข้อมูลที่สม่ำเสมอ รักษาการจัดรูปแบบอย่างมีความหลากหลาย และให้ความสะดวกในการแบ่งปันเอกสารในสภาพแวดล้อมที่หลากหลาย

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}

- **การแบ่งปันเอกสารข้ามแพลตฟอร์ม** – ส่งเนื้อหาที่มีการจัดรูปแบบที่สามารถเข้าถึงได้บนอุปกรณ์และเครื่องมือสร้างข้อความหลายรายการ
- **รายงานที่มีน้ำหนักเบา** – สร้างรายงานที่กระชับและอ่านง่ายจากข้อมูล JSON โครงสร้าง
- **ความเข้ากันได้กับระบบโบราณ** – ให้ความมั่นใจว่าเอกสารทำงานได้กับซอฟต์แวร์และระบบองค์กรที่เก่า
- **เอกสารที่พกพาได้** – สร้างไฟล์ Rich Text ที่สามารถถ่ายโอนได้ง่ายสำหรับการใช้ทั่วไป
- **ข้อความที่จัดรูปแบบจากข้อมูล** – แปลงชุดข้อมูลโครงสร้างเป็นเอกสารที่มีรูปแบบและอ่านง่าย

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การใช้งานอัตโนมัติ" %}}

- **กระแสข้อมูล JSON เป็น RTF** – อัตโนมัติการแปลงข้อมูลโครงสร้างเป็นไฟล์ Rich Text
- **รายงานที่จัดรูปแบบอัตโนมัติ** – สร้างรายงานที่มีรูปแบบโดยตรงจากแหล่งข้อมูล JSON
- **ความเข้ากันได้ของเอกสารที่ขับเคลื่อนด้วย JSON** – เปิดใช้เนื้อหาที่มีความเหมือนกันในแพลตฟอร์มและระบบ
- **กระบวนการกระจายเอกสาร RTF ขององค์กร** – มาตรฐานเอกสาร Rich Text สำหรับการใช้งานขนาดใหญ่ขององค์กร

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}