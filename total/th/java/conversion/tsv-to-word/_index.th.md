---
title: แปลง TSV เป็น WORD โดยใช้ Java
description: Java API เพื่อส่งออก TSV เป็น WORD โดยใช้ Excel หรือ Word
url_ignore: /th/java/conversion/tsv-to-word/
family: total
platformtag: net
feature: conversion
informat: TSV
outformat: WORD
otherformats: PPTX WORD POWERPOINT WORDX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อส่งออก TSV เป็น WORD" h2="บน Premise Java API เพื่อส่งออก TSV ไปยัง WORD โดยไม่ต้องพึ่ง Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแสดงผล TSV เป็น WORD เป็นกระบวนการสองขั้นตอน ก่อนอื่น คุณจะต้องใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java) API เพื่อแปลงเอกสาร TSV ที่ระบุเป็น PDF จากนั้นใช้ [Aspose.Pdf สำหรับ Java](https://products.aspose.com/pdf/java) API คุณสามารถแปลงเอกสาร PDF เป็น WORD ได้อย่างง่ายดาย API ทั้งสองอยู่ภายใต้คอลเล็กชันของไลบรารีอัตโนมัติรูปแบบไฟล์ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง TSV เป็น WORD ผ่าน Java API" %}}
1. เปิดไฟล์ TSV โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. แปลง TSV เป็น PDF และตั้งค่า SaveFormat เป็น AUTO
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. บันทึกเอกสารในรูปแบบ WORD โดยใช้ [บันทึก](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) วิธีการและตั้งค่า Word เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณต้องใช้ Aspose.Total สำหรับ Java โดยตรงจากโครงการที่ใช้ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และรวมไลบรารี่ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/tsv-to-wordx/" name="TSV ถึง WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/tsv-to-pptx/" name="TSV ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/tsv-to-powerpoint/" name="TSV ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/tsv-to-word/" name="TSV ถึง WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}