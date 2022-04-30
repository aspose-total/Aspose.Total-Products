---
title: แปลง XLTM เป็น DOCX โดยใช้ Java
description: Java API เพื่อส่งออก XLTM เป็น DOCX โดยใช้ Excel หรือ Word
url: /th/java/conversion/xltm-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: DOCXX
otherformats: POWERPOINT PPTX DOCX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อส่งออก XLTM เป็น DOCX" h2="บน Premise Java API เพื่อส่งออก XLTM ไปยัง DOCX โดยไม่ต้องพึ่ง Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแสดงผล XLTM เป็น DOCX เป็นกระบวนการสองขั้นตอน ก่อนอื่น คุณจะต้องใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java) API เพื่อแปลงเอกสาร XLTM ที่ระบุเป็น PDF จากนั้นใช้ [Aspose.Pdf สำหรับ Java](https ://products.aspose.com/pdf/java) API คุณสามารถแปลงเอกสาร PDF เป็น DOCX ได้อย่างง่ายดาย API ทั้งสองอยู่ภายใต้คอลเล็กชันของไลบรารีอัตโนมัติรูปแบบไฟล์ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง XLTM เป็น DOCX ผ่าน Java API" %}}
1. เปิดไฟล์ XLTM โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. แปลง XLTM เป็น PDF และตั้งค่า SaveFormat เป็น AUTO
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Docxument](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Docxument)
4. บันทึกเอกสารในรูปแบบ DOCX โดยใช้ [บันทึก](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions-) วิธีการและตั้งค่า Docx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณต้องใช้ Aspose.Total สำหรับ Java โดยตรงจากโครงการที่ใช้ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และรวมไลบรารี่ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// save XLTM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCXX format
docxument.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xltm-to-docxx/" name="XLTM ถึง DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xltm-to-pptx/" name="XLTM ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xltm-to-powerpoint/" name="XLTM ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xltm-to-word/" name="XLTM ถึง WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}