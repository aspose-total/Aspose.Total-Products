---
title: แปลง FODS เป็น PPTX โดยใช้ Java
description: Java API เพื่อส่งออก FODS เป็น PPTX โดยใช้ Excel หรือ Word
url_ignore: /th/java/conversion/fods-to-pptx/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: PPTX
otherformats: PPTX POWERPOINT PPTXX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อส่งออก FODS เป็น PPTX" h2="บน Premise Java API เพื่อส่งออก FODS ไปยัง PPTX โดยไม่ต้องพึ่ง Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแสดงผล FODS เป็น PPTX เป็นกระบวนการสองขั้นตอน ก่อนอื่น คุณจะต้องใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java) API เพื่อแปลงเอกสาร FODS ที่ระบุเป็น PDF จากนั้นใช้ [Aspose.Pdf สำหรับ Java](https://products.aspose.com/pdf/java) API คุณสามารถแปลงเอกสาร PDF เป็น PPTX ได้อย่างง่ายดาย API ทั้งสองอยู่ภายใต้คอลเล็กชันของไลบรารีอัตโนมัติรูปแบบไฟล์ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง FODS เป็น PPTX ผ่าน Java API" %}}
1. เปิดไฟล์ FODS โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. แปลง FODS เป็น PDF และตั้งค่า SaveFormat เป็น AUTO
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. บันทึกเอกสารในรูปแบบ PPTX โดยใช้ [บันทึก](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) วิธีการและตั้งค่า Pptx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณต้องใช้ Aspose.Total สำหรับ Java โดยตรงจากโครงการที่ใช้ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และรวมไลบรารี่ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/fods-to-pptxx/" name="FODS ถึง PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/fods-to-pptx/" name="FODS ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/fods-to-powerpoint/" name="FODS ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/fods-to-word/" name="FODS ถึง WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}