---
title: Java API เพื่อแสดงผล SVG เป็น SXC
description: ส่งออก SVG เป็น SXC ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/java/conversion/svg-to-sxc/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: SXC
otherformats: ODS XLTM EXCEL TXT XLSM SXC MD DIF XLSB XLAM XLT FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก SVG เป็น SXC ผ่าน Java" h2="แปลงไฟล์ SVG เป็น SXC โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถรวมคุณลักษณะการแปลง SVG เป็น SXC ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถแสดง SVG เป็น XLSX ในขั้นตอนที่ 2 คุณสามารถแปลง XLSX เป็น SXC ได้โดยใช้ Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ SVG เป็น SXC ผ่าน Java" %}}
1. เปิดไฟล์ SVG โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง SVG เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
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
หากเอกสาร SVG ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น SXC ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง SVG ที่ได้รับการป้องกันเป็น SXC ผ่าน Java" %}}
ในขณะที่แปลงไฟล์ SVG เป็น SXC คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ SXC เอาต์พุตของคุณ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ XLSX ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น SXC ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

การแปลง SVG เป็น SXC (StarOffice/LibreOffice Spreadsheet) ช่วยให้สามารถฝังแผนภูมิเวกเตอร์ลงในรูปแบบสเปรดชีตโอเพนซอร์สได้ SXC เหมาะสำหรับการทำงานร่วมกันและความเข้ากันได้ของสเปรดชีตที่เป็นแพลตฟอร์ม跨กัน

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}

* นำเข้าแดชบอร์ดการเงินหรือโครงการจาก SVG เข้าสู่สเปรดชีต LibreOffice
* แบ่งปันข้อมูลวิจัยหรือข้อมูลทางวิชาการพร้อมแผนภูมิเวกเตอร์ในไฟล์ SXC
* สเปรดชีตการติดตามโครงการร่วมกันโดยใช้ภาพแบบ SVG ที่ฝังอยู่
* แม่แบบสเปรดชีตโอเพนซอร์สมาตรฐานพร้อมไดอะแกรมแบบอินเทอร์แอคทีฟ

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}

* การแปลงไฟล์ SVG เป็น SXC แบบกลุ่มอัตโนมัติสำหรับท่อการรายงาน
* การส่งออกแดชบอร์ดที่ใช้ SVG ตามกำหนดเวลาเข้าสู่สเปรดชีตโอเพนซอร์ส
* การรวมกับชุดสำนักงานร่วมกันเพื่อให้ทีมสามารถเข้าถึงได้ทั่วไป
* การสร้างสเปรดชีต SXC จากข้อมูล SVG แบบไดนามิกโดยเรียกใช้

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}