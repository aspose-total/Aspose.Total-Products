---
title: Java API เพื่อแสดงผล EPUB เป็น TXT
description: ส่งออก EPUB เป็น TXT ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/java/conversion/epub-to-txt/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: TXT
otherformats: ODS XLTX EXCEL XLSM XLAM FODS XLSB XLTM TXT XLT DIF SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก EPUB เป็น TXT ผ่าน Java" h2="แปลงไฟล์ EPUB เป็น TXT โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถรวมคุณลักษณะการแปลง EPUB เป็น TXT ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถแสดง EPUB เป็น XLSX ในขั้นตอนที่ 2 คุณสามารถแปลง XLSX เป็น TXT ได้โดยใช้ Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ EPUB เป็น TXT ผ่าน Java" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง EPUB เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
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
หากเอกสาร EPUB ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น TXT ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง EPUB ที่ได้รับการป้องกันเป็น TXT ผ่าน Java" %}}
ในขณะที่แปลงไฟล์ EPUB เป็น TXT คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ TXT เอาต์พุตของคุณ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ XLSX ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น TXT ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **EPUB เป็น TXT** เป็นสิ่งสำคัญสำหรับการสร้าง **รูปแบบข้อความธรรมดา** ของสิ่งพิมพ์ดิจิทัล ไฟล์ TXT ให้เนื้อหาที่มีน้ำหนักเบา สามารถเข้าถึงได้ทั่วไป และสามารถทำดัชนีเนื้อหาได้ง่าย โดยการแปลง eBook เป็นข้อความธรรมดา สำนักพิมพ์ นักวิจัย และนักพัฒนาสามารถเปิดใช้งานการเก็บรักษาข้อมูลอย่างรวดเร็ว การเข้าถึงบนหลายแพลตฟอร์มอย่างไม่มีข้อจำกัด และการนำเนื้อหากลับมาใช้ใน AI เครื่องมือค้นหา และกระบวนการทำงานทางการพิมพ์

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}
- **การเก็บรักษาข้อมูลอย่างเบา** – เก็บเนื้อหาได้อย่างมีประสิทธิภาพโดยไม่มีความซับซ้อนในการจัดรูปแบบ
- **ความสามารถในการเข้าถึงบนหลายแพลตฟอร์ม** – เปิดไฟล์ข้อความ eBook บนอุปกรณ์หรือระบบปฏิบัติการเกือบทุกชนิด
- **ชุดข้อมูล eBook สู่เครื่องมือค้นหา** – สร้างชุดข้อมูลข้อความที่ถูกปรับแต่งให้เหมาะสำหรับการจัดดัชนีและการเรียกคืนข้อมูล
- **การสกัดเอาเนื้อหาสำหรับการฝึก AI** – ใส่ข้อความธรรมดาลงในโมเดลประมวลผลภาษาธรรมชาติ
- **กระบวนการทำงานการพิมพ์อย่างรวดเร็ว** – ส่งเสริมกระบวนการกระจายโดยใช้ไฟล์ข้อความที่ไม่มีรูปแบบ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}
- **กระบวนการทำงาน EPUB เป็น TXT** – ทำให้การแปลงเป็นระบบทำงานอัตโนมัติสำหรับกระบวนการทำงานการพิมพ์ที่เรียบง่าย
- **การแปลงข้อความธรรมดาเป็นจำนวนมาก** – ประมวลผลคอลเล็กชัน eBook ขนาดใหญ่เป็นรูปแบบ TXT
- **การสกัดเอาเมตาดาต้าเข้าสู่ไฟล์ TXT** – ส่งออกข้อมูลหนังสือโครงสร้างเข้าไฟล์ข้อความที่มีน้ำหนักเบา
- **การทำดัชนีเนื้อหาโดยอัตโนมัติ** – เปิดให้การค้นหาเร็วขึ้นและฉลาดขึ้นด้วยเวอร์ชันข้อความที่ไม่มีรูปแบบ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}