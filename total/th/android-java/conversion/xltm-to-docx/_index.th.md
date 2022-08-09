---
title: ส่งออก XLTM เป็น DOCX ใน Android
description: Android API เพื่อแปลง XLTM เป็น DOCX โดยไม่ต้องใช้ Microsoft Word
url: /th/android-java/conversion/xltm-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: DOCX
otherformats: PPTX WORD DOC POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดงผล XLTM เป็น DOCX บน Android ผ่าน Java" h2="แปลง XLTM เป็น DOCX ภายในแอปพลิเคชัน Android ของคุณโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ Android ผ่าน Java](https://products.aspose.com/total/android-java/) เป็นแพ็คเกจของ File Automation API ที่ทรงพลัง ด้วยการใช้ API สองอัน คุณสามารถรวมคุณลักษณะการแปลง XLTM เป็น DOCX ในแอปพลิเคชัน Android ของคุณได้ ในขั้นตอนแรก คุณสามารถส่งออก XLTM เป็น PDF ได้โดยใช้ [Aspose.Cells สำหรับ Android ผ่าน Java](https://products.aspose.com/cells/android-java/) หลังจากนั้น ด้วยการใช้ [Aspose.PDF สำหรับ Android ผ่าน Java](https://products.aspose.com/pdf/android-java/) คุณจะสามารถแปลง PDF เป็น DOCX ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อส่งออก XLTM เป็น DOCX" %}}
1. เปิดไฟล์ XLTM โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. แปลง XLTM เป็น PDF และตั้งค่า SaveFormat เป็น AUTO
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument)
4. บันทึกเอกสารในรูปแบบ DOCX โดยใช้ [บันทึก](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Android ผ่าน Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.PDF สำหรับ Android ผ่าน Java](https://docxs.aspose.com/pdf/androidjava/installation/) และ [Aspose.Cells สำหรับ Android ผ่าน Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// save XLTM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ลบคุณสมบัติที่กำหนดเองออกจากไฟล์ XLTM ใน Android ผ่าน Java" %}}
นอกจากการแปลงเอกสารแล้ว [Aspose.Cells สำหรับ Android ผ่าน Java](https://products.aspose.com/cells/android-java/) ยังมีฟีเจอร์อื่นๆ อีกเป็นจำนวนมากอีกด้วย ก่อนขั้นตอนการแปลง คุณสามารถลบคุณสมบัติที่กำหนดเองของเอกสาร XLTM ได้ หากต้องการลบคุณสมบัติที่กำหนดเอง ให้เรียกเมธอด [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) และส่งชื่อ คุณสมบัติของเอกสารที่จะลบออก
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTM file using Workbook class
Workbook book = new Workbook("input.xltm");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xltm-to-pptx/" name="XLTM ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xltm-to-word/" name="XLTM ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xltm-to-docx/" name="XLTM ถึง DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xltm-to-powerpoint/" name="XLTM ถึง POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}