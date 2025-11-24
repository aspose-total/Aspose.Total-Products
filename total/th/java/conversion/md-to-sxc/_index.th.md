---
title: Java API เพื่อแสดงผล MD เป็น SXC
description: ส่งออก MD เป็น SXC ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/java/conversion/md-to-sxc/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: SXC
otherformats: DIF EXCEL TXT XLTM SXC XLT XLTX XLSM XLSB FODS XLAM TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก MD เป็น SXC ผ่าน Java" h2="แปลงไฟล์ MD เป็น SXC โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถรวมคุณลักษณะการแปลง MD เป็น SXC ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถแสดง MD เป็น XLSX ในขั้นตอนที่ 2 คุณสามารถแปลง XLSX เป็น SXC ได้โดยใช้ Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ MD เป็น SXC ผ่าน Java" %}}
1. เปิดไฟล์ MD โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง MD เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ SXC โดยใช้ [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ใน pom.xml ของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
หากเอกสาร MD ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น SXC ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง MD ที่ได้รับการป้องกันเป็น SXC ผ่าน Java" %}}
ในขณะที่แปลงไฟล์ MD เป็น SXC คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ SXC เอาต์พุตของคุณ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ XLSX ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น SXC ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



การแปลง MD (Markdown) เป็น SXC (StarOffice Calc) มีประโยชน์ต่อองค์กรที่ยังใช้สภาพแวดล้อมสเปรดชีต StarOffice/OpenOffice เวอร์ชันเก่า ๆ  SXC รองรับสูตรคำนวณ โครงสร้างแผ่นงาน และการจัดรูปแบบเซลล์ที่เข้ากันได้กับระบบสำนักงานเก่า



{{% blocks/products/pf/agp/feature-section-col title="กรณีการใช้งานหลัก" %}}



* การย้ายตาราง Markdown เข้าสู่สเปรดชีต SXC เวอร์ชันเก่า

* การอัปเดตระบบองค์กรที่เก่ากว่าด้วยข้อมูลที่มี MD-based

* การสร้างไฟล์ SXC สำหรับแพลตฟอร์มที่เก่าแต่ยังใช้งานได้

* เตรียมบันทึกวิศวกรรมจาก Markdown เป็นรูปแบบสเปรดชีตคลาสสิก



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}



* การแปลง MD เป็น SXC แบบกลุ่มสำหรับเครื่องมือธุรกิจสำหรับการเก็บถาวร

* การเชื่อมต่อ ETL สำหรับซอฟต์แวร์รัฐบาลหรืออุตสาหกรรมเก่า

* การสร้าง SXC รายวันจากคลังข้อมูล Markdown

* การสร้าง SXC ตามเงื่อนไขสำหรับขั้นตอนการทำงานที่เข้ากันได้ย้อนหลัง



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}