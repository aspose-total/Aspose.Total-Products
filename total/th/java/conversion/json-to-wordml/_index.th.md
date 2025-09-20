---
title: แปลงรูปแบบ JSON เป็น WORDML ผ่าน Java
description: แยก JSON เป็น WORDML ใน Java โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/json-to-wordml/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WORDML
otherformats: FLATOPC PS RTF DOC MOBI WORDML DOCM DOT PCL DOTX EPUB OTT WORD ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น WORDML ผ่าน Java" h2="Java API ในตัวเพื่อแยก JSON เป็น WORDML โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถแปลง JSON เป็น WORDML ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณสามารถแยก JSON เป็น PDF ในขั้นตอนที่ 2 คุณสามารถแปลง PDF เป็น WORDML โดยใช้ Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น WORDML ผ่าน Java" %}}
1. สร้าง [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. นำเข้าไฟล์ JSON ไปยังเวิร์กชีตโดยใช้คลาส [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) และ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) เป็น PDF
3. โหลดเอกสาร PDF โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ WORDML โดยใช้ [บันทึก](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) กระบวนการ
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
นอกจากนี้ API ยังให้คุณตั้งค่าตัวเลือกเลย์เอาต์สำหรับ JSON ของคุณในขณะที่แยกวิเคราะห์ JSON เป็น WORDML โดยใช้ [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่า null ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น WORDML ผ่าน Java" %}}
เมื่อใช้ API คุณสามารถแยก JSON เป็น WORDML ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร WORDML ของคุณ ก่อนอื่นให้แปลงไฟล์ JSON เป็น PDF และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PDF ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติของมัน วิธี Call Watermark.setText และส่งข้อความลายน้ำ & วัตถุของ TextWatermarkOptions หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปที่ WORDML 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **JSON เป็น WORDML** เป็นสิ่งจำเป็นสำหรับการสร้าง **WordprocessingML (เอกสาร Word ที่ใช้ XML) จากข้อมูลโครงสร้าง**  WORDML ทำให้การแลกเปลี่ยนข้อมูลเป็นไปอย่างราบรื่น การสร้างเอกสารตามแม่แบบ และเข้ากันได้กับขั้นตอนการทำงานที่ใช้ XML โดยการแปลง JSON เป็น WORDML องค์กรสามารถอัตโนมัติสร้างเอกสาร รักษาความสมบูรณ์ของเนื้อหาโครงสร้าง และสนับสนุนการเผยแพร่ในองค์กร รัฐบาล และสำนักพิมพ์ทางวิชาการได้อย่างมีประสิทธิภาพ  

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}

- **การแลกเปลี่ยนข้อมูลระหว่างระบบ** – สะดวกในการใช้รูปแบบเอกสารที่สามารถทำงานร่วมกันสำหรับแอปพลิเคชันขององค์กร  
- **การจัดเก็บเอกสารขององค์กร** – รักษาไฟล์ Word ที่ใช้ XML โครงสร้างสำหรับการจัดเก็บในระยะยาว  
- **การสร้างเอกสารตามแม่แบบ** – อัตโนมัติสร้างเอกสารมาตรฐานจากแม่แบบ  
- **การเก็บถาวรของรัฐบาล** – สร้างเอกสาร Word ที่เป็นไปตามข้อกำหนด พร้อมใช้งานกับข้อมูลทาง XML สำหรับบันทึกข้อมูลทางการ  
- **การเผยแพร่ทางวิชาการที่มีโครงสร้าง** – สร้างเอกสารวิจัยและเนื้อหาการศึกษาในรูปแบบโครงสร้าง  

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การอัตโนมัติ" %}}

- **กระแสงาน JSON เป็น WordML** – อัตโนมัติการแปลงข้อมูลโครงสร้างเป็นเอกสาร Word ที่ใช้ XML  
- **การสร้างเอกสาร XML โดยอัตโนมัติ** – ปรับปรุงกระบวนการสร้างเอกสารเป็นก้อนใหญ่โดยรักษาโครงสร้าง  
- **กระบวนการทำงานเอกสารที่ใช้ JSON** – เติมข้อมูลลงในไฟล์ WordML โดยตรงจากชุดข้อมูลโครงสร้าง  
- **การรายงานโครงสร้างระดับองค์กร** – ขยายการสร้างเอกสารโครงสร้างอัตโนมัติในแผนกต่าง ๆ ขององค์กรอย่างมีประสิทธิภาพ  

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}