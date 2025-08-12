---
title: Java API เพื่อแสดงผล CGM เป็น TXT
description: ส่งออก CGM เป็น TXT ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/java/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL TXT XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก CGM เป็น TXT ผ่าน Java" h2="แปลงไฟล์ CGM เป็น TXT โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถรวมคุณลักษณะการแปลง CGM เป็น TXT ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถแสดง CGM เป็น XLSX ในขั้นตอนที่ 2 คุณสามารถแปลง XLSX เป็น TXT ได้โดยใช้ Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ CGM เป็น TXT ผ่าน Java" %}}
1. เปิดไฟล์ CGM โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง CGM เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ TXT โดยใช้ [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ใน pom.xml ของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
หากเอกสาร CGM ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น TXT ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง CGM ที่ได้รับการป้องกันเป็น TXT ผ่าน Java" %}}
ในขณะที่แปลงไฟล์ CGM เป็น TXT คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ TXT เอาต์พุตของคุณ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ XLSX ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น TXT ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
การแปลงไฟล์ **Computer Graphics Metafile (CGM)** เป็นรูปแบบ **TXT (Plain Text)** มีความคุ้มค่าสำหรับการสกัด, บันทึก, และประมวลผลข้อมูลกราฟิกเวกเตอร์ในรูปแบบที่เป็นมนุษย์อ่านได้แบบเบา ใน **กระแสข้อมูลที่ขับเคลื่อนด้วย Java**, การแปลงนี้ช่วยให้เกิดการเปลี่ยนแปลงของแผนภาพ CGM เป็นรูปแบบข้อความสำหรับการบันทึกข้อมูล, เก็บข้อมูล metadata, หรือการวิเคราะห์ล่างสุด โดยการจับข้อมูลที่อธิบายในไฟล์ CGM เป็น TXT, องค์กรสามารถทำให้การผสมผสานกับระบบอื่นเป็นเรื่องง่าย, เปิดโอกาสให้ค้นหาและทำดัชนีอย่างรวดเร็ว, และรักษาความเข้ากันได้ในระยะยาว.



## ✅ การใช้งานหลัก

- **การบันทึกแผนภาพเป็นข้อความ**  
  เก็บข้อมูลแผนภาพ CGM เป็นข้อความเพื่อการตรวจสอบ, การแก้ไขข้อผิดพลาด, หรือเก็บไว้เป็นประวัติ.

- **การสกัดข้อมูลเวกเตอร์กราฟิก**  
  แปลงโครงสร้าง CGM เป็น TXT เพื่อการวิเคราะห์, การทำดัชนีค้นหา, หรือการผสมผสานกับเครื่องมือวิเคราะห์.

- **เอกสาร metadata ทางวิศวกรรม**  
  เอกสารข้อมูลวิศวกรรมที่เกี่ยวข้องกับ CGM ในไฟล์ TXT เพื่อการอ้างอิงอย่างรวดเร็วและการเก็บข้อมูลเบา.



## ⚙️ สถานการณ์การอัตโนมัติ

- **ไลบรารี I/O ของ Java สำหรับการแปลง**  
  ใช้ API การจัดการไฟล์ของ Java มาพร้อมกับตัวแยกวิเคราะห์ CGM เพื่อสกัดและเขียนเนื้อหาไปยังไฟล์ TXT.

- **บริการตรวจสอบไฟล์**  
  อัตโนมัติการแปลง CGM เป็น TXT โดยตรวจสอบไดเรกทอรีด้วย Java `WatchService` สำหรับเหตุการณ์ไฟล์ใหม่.

- **งานแปลงเป็นชุด**  
  ประมวลผลปริมาณมากของไฟล์ CGM ในงาน Java ที่กำหนดเวลา, ส่งออกเป็นรูปแบบข้อความสำหรับการเก็บไว้หรือการวิเคราะห์.

- **ผู้ส่งออกข้อความเป็นข้อความธรรมดาในกระบวนการ ETL Pipelines**  
  ผสมผสานการตัดสินใจ CGM และการส่งออกเป็น TXT เข้ากับกระบวนการการทำงานข้อมูลโครงสร้างที่ขับเคลื่อนด้วย Java.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}