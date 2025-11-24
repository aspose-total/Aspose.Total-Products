---
title: Java API เพื่อแสดงผล MHTML เป็น FODS
description: ส่งออก MHTML เป็น FODS ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/java/conversion/mhtml-to-fods/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: FODS
otherformats: MD SXC FODS TSV XLT TXT XLSB XLSM EXCEL DIF XLAM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก MHTML เป็น FODS ผ่าน Java" h2="แปลงไฟล์ MHTML เป็น FODS โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถรวมคุณลักษณะการแปลง MHTML เป็น FODS ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถแสดง MHTML เป็น XLSX ในขั้นตอนที่ 2 คุณสามารถแปลง XLSX เป็น FODS ได้โดยใช้ Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ MHTML เป็น FODS ผ่าน Java" %}}
1. เปิดไฟล์ MHTML โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง MHTML เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ FODS โดยใช้ [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ใน pom.xml ของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
หากเอกสาร MHTML ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น FODS ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง MHTML ที่ได้รับการป้องกันเป็น FODS ผ่าน Java" %}}
ในขณะที่แปลงไฟล์ MHTML เป็น FODS คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ FODS เอาต์พุตของคุณ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ XLSX ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น FODS ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



การแปลง MHTML เป็น FODS (Flat OpenDocument Spreadsheet) สร้างไฟล์สเปรดชีตที่เปิดเผยและใช้ XML ที่เหมาะสำหรับ LibreOffice หรือ OpenOffice  FODS เหมาะสำหรับการเก็บข้อมูลแบบเบา และพกพาได้



{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}



* เก็บข้อมูลรายงานแบบตารางบนเว็บสำหรับการแก้ไขในหลายแพลตฟอร์ม

* เตรียมเทมเพลตสเปรดชีตโอเพนซอร์สสำหรับทีมที่ทำงานร่วมกัน

* แปลงแดชบอร์ดการเงินออนไลน์เป็นไฟล์ FODS ที่สามารถพกพาได้

* แชร์ข้อมูลเว็บโครงสร้างกับผู้ใช้ที่ไม่ใช้ Excel



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}



* การแปลง MHTML เป็น FODS ตามกำหนดเวลาสำหรับการทำงานของสำนักงานโอเพนซอร์ส

* ประมวลผลเป็นชุดของตารางออนไลน์เพื่อสร้างไฟล์ FODS ที่สามารถแก้ไขได้

* การแปลงอัตโนมัติที่เรียกใช้งานสำหรับระบบตรวจสอบเว็บ

* การรวมเข้ากับแพลตฟอร์มที่ต้องการเทมเพลต FODS สำหรับการทำงานร่วมกัน



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}