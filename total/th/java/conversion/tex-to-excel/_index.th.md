---
title: Java API เพื่อแสดงผล TEX เป็น EXCEL
description: ส่งออก TEX เป็น EXCEL ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/java/conversion/tex-to-excel/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: EXCEL
otherformats: DIF ODS XLTX XLTM XLSB TSV XLT TXT FODS MD EXCEL XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก TEX เป็น EXCEL ผ่าน Java" h2="แปลงไฟล์ TEX เป็น EXCEL โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถรวมคุณลักษณะการแปลง TEX เป็น EXCEL ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถแสดง TEX เป็น XLSX ในขั้นตอนที่ 2 คุณสามารถแปลง XLSX เป็น EXCEL ได้โดยใช้ Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ TEX เป็น EXCEL ผ่าน Java" %}}
1. เปิดไฟล์ TEX โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง TEX เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ EXCEL โดยใช้ [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ใน pom.xml ของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
หากเอกสาร TEX ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น EXCEL ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง TEX ที่ได้รับการป้องกันเป็น EXCEL ผ่าน Java" %}}
ในขณะที่แปลงไฟล์ TEX เป็น EXCEL คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ EXCEL เอาต์พุตของคุณ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ XLSX ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น EXCEL ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



การแปลง TEX เป็น **EXCEL (XLS/XLSX)** ช่วยให้เอกสาร LaTeX ที่มีตารางและสูตรได้รับการผสมผสานอย่างเต็มที่ใน Microsoft Excel สำหรับการวิเคราะห์ การแสดงผล และรายงานอย่างมืออาชีพ.



{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}



* รายงานการเงินที่มีสูตรที่สร้างจาก LaTeX.

* การคำนวณวิศวกรรมสำหรับการวิเคราะห์สเปรดชีทที่ซับซ้อน.

* แผ่นคะแนนการตรวจคะแนนทางวิชาการและชุดข้อมูลวิจัย.

* แดชบอร์ดแบบอินเทอร์แอคที่รวมตาราง LaTeX และแผนภูมิ Excel.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}



* การแปลง LaTeX เป็น Excel แบบกลุ่มสำหรับการรายงานของสถาบัน.

* การผสมผสานกับเครื่องมือธุรกิจอัจฉริยะที่ใช้ Excel อัตโนมัติ.

* การอัพเดทที่เรียกใช้สำหรับสเปรดชีทความก้าวหน้าของโครงการ.

* การแปลงเป็นเรียลไทม์สำหรับการทำงานร่วมกับ Excel บนคลาวด์.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}