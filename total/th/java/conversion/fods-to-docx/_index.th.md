---
title: แปลง FODS เป็น DOCX โดยใช้ Java หรือด้วยตัวแปลงออนไลน์ฟรี
description: Java API เพื่อส่งออก FODS เป็น DOCX หรือทางออนไลน์ โดยใช้ Excel หรือ Word หรือทางออนไลน์ ทดสอบตัวแปลง CSV เป็น DOC ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด
url_ignore: /th/java/conversion/fods-to-docx/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: DOCX
otherformats: POWERPOINT WORD DOCX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อส่งออก FODS เป็น DOCX หรือทางออนไลน์" h2="บน Premise Java API เพื่อส่งออก FODS ไปยัง DOCX โดยไม่ต้องพึ่ง Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแสดงผล FODS เป็น DOCX เป็นกระบวนการสองขั้นตอน ก่อนอื่น คุณจะต้องใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java) API เพื่อแปลงเอกสาร FODS ที่ระบุเป็น PDF จากนั้นใช้ [Aspose.Pdf สำหรับ Java](https://products.aspose.com/pdf/java) API คุณสามารถแปลงเอกสาร PDF เป็น DOCX ได้อย่างง่ายดาย API ทั้งสองอยู่ภายใต้คอลเล็กชันของไลบรารีอัตโนมัติรูปแบบไฟล์ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง FODS เป็น DOCX ผ่าน Java API" %}}
1. เปิดไฟล์ FODS โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. แปลง FODS เป็น PDF และตั้งค่า SaveFormat เป็น AUTO
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. บันทึกเอกสารในรูปแบบ DOCX โดยใช้ [บันทึก](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) วิธีการและตั้งค่า Docx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณต้องใช้ Aspose.Total สำหรับ Java โดยตรงจากโครงการที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์สำหรับ FODS เป็น DOCX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=fods" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/fods-to-docx/">ลองใช้แอปฟรีของเราสำหรับการแปลง FODS เป็น DOCX</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}DOCX
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/fods-to-docxx/" name="FODS ถึง DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/fods-to-pptx/" name="FODS ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/fods-to-powerpoint/" name="FODS ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/fods-to-word/" name="FODS ถึง WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}