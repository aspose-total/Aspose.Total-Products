---
title: Java API เพื่อแสดงผล EPUB เป็น ODS
description: ส่งออก EPUB เป็น ODS ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/java/conversion/epub-to-ods/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: ODS
otherformats: MD DIF TXT XLSB FODS XLSM TSV XLT SXC XLTX ODS EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก EPUB เป็น ODS ผ่าน Java" h2="แปลงไฟล์ EPUB เป็น ODS โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถรวมคุณลักษณะการแปลง EPUB เป็น ODS ในแอปพลิเคชัน Java ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถแสดง EPUB เป็น XLSX ในขั้นตอนที่ 2 คุณสามารถแปลง XLSX เป็น ODS ได้โดยใช้ Spreadsheet Programming API [Aspose.Cells for Java](https://products.aspose.com/cells/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ EPUB เป็น ODS ผ่าน Java" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง EPUB เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ ODS โดยใช้ [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ใน pom.xml ของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
หากเอกสาร EPUB ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น ODS ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง EPUB ที่ได้รับการป้องกันเป็น ODS ผ่าน Java" %}}
ในขณะที่แปลงไฟล์ EPUB เป็น ODS คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ ODS เอาต์พุตของคุณ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ XLSX ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น ODS ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **EPUB เป็น ODS (OpenDocument Spreadsheet)** เป็นสิ่งจำเป็นสำหรับการสร้าง **สเปรดชีตมาตรฐานเปิด** จากการตีพิมพ์ดิจิทัล ไฟล์ ODS ให้รูปแบบที่ยืดหยุ่นและเข้ากันได้กว้างขวางสำหรับการจัดระเบียบและวิเคราะห์ข้อมูลโครงสร้าง โดยการแปลง EPUB เป็น ODS ผู้สอน นักวิจัย ห้องสมุด และสำนักพิมพ์สามารถจัดการข้อมูลเมตาดาต้า ติดตามชุดข้อมูลวิจัย และปรับปรุงกระบวนการทำงานในการตีพิมพ์ที่ใช้ข้อมูลได้อย่างมีประสิทธิภาพ

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}
- **การจัดการชุดข้อมูลทางวิชาการ** – จัดระเบียบและบำรุงรักษาข้อมูลวิจัยจาก eBook ในรูปแบบสเปรดชีต
- **บันทึกข้อมูลในสารบรรณของห้องสมุด** – จัดเรียงเมตาดาต้าที่เป็นเอกสารสำหรับการเข้าถึงและวิเคราะห์
- **การจัดเรียงเมตาดาต้า** – แปลงเมตาดาต้าจาก eBook เป็นตารางสเปรดชีตโครงสร้าง
- **การวิเคราะห์ข้อมูลวิจัย** – สะดวกสบายในการคำนวณ เรียงลำดับ และรายงานโดยใช้ไฟล์ ODS
- **กระบวนการทำงานในการตีพิมพ์** – มาตรฐานการจัดการข้อมูลในการตีพิมพ์ทางวิชาการและบรรณาธิกรรม

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}
- **ท่อการแปลง EPUB เป็น ODS** – อัตโนมัติการแปลง eBook เป็นสเปรดชีตโครงสร้าง
- **การแปลงสเปรดชีตโดยอัตโนมัติ** – ปรับปรุงการประมวลผลเมตาดาต้าและชุดข้อมูลในขอบเขตขนาดใหญ่
- **การสกัดชุดข้อมูลเป็นกลุ่ม** – สกัดข้อมูล eBook ปริมาณมากอย่างมีประสิทธิภาพ
- **การวิเคราะห์ข้อมูลการตีพิมพ์ระดับองค์กร** – รวมไฟล์ ODS ลงในกระบวนการวิเคราะห์และรายงาน

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}