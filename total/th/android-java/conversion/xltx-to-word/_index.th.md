---
title: ส่งออก XLTX เป็น WORD ใน Android
description: Android API เพื่อแปลง XLTX เป็น WORD โดยไม่ต้องใช้ Microsoft Word
url: /th/android-java/conversion/xltx-to-word/
family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: DOC
otherformats: PPTX POWERPOINT DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดงผล XLTX เป็น WORD บน Android ผ่าน Java" h2="แปลง XLTX เป็น WORD ภายในแอปพลิเคชัน Android ของคุณโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ Android ผ่าน Java](https://products.aspose.com/total/android-java/) เป็นแพ็คเกจของ File Automation API ที่ทรงพลัง ด้วยการใช้ API สองอัน คุณสามารถรวมคุณลักษณะการแปลง XLTX เป็น WORD ในแอปพลิเคชัน Android ของคุณได้ ในขั้นตอนแรก คุณสามารถส่งออก XLTX เป็น PDF ได้โดยใช้ [Aspose.Cells สำหรับ Android ผ่าน Java](https://products.aspose.com/cells/android-java/) หลังจากนั้น ด้วยการใช้ [Aspose.PDF สำหรับ Android ผ่าน Java](https://products.aspose.com/pdf/android-java/) คุณจะสามารถแปลง PDF เป็น WORD ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อส่งออก XLTX เป็น WORD" %}}
1. เปิดไฟล์ XLTX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. แปลง XLTX เป็น PDF และตั้งค่า SaveFormat เป็น AUTO
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. บันทึกเอกสารในรูปแบบ WORD โดยใช้ [บันทึก](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Android ผ่าน Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.PDF สำหรับ Android ผ่าน Java](https://words.aspose.com/pdf/androidjava/installation/) และ [Aspose.Cells สำหรับ Android ผ่าน Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// save XLTX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ลบคุณสมบัติที่กำหนดเองออกจากไฟล์ XLTX ใน Android ผ่าน Java" %}}
นอกจากการแปลงเอกสารแล้ว [Aspose.Cells สำหรับ Android ผ่าน Java](https://products.aspose.com/cells/android-java/) ยังมีฟีเจอร์อื่นๆ อีกเป็นจำนวนมากอีกด้วย ก่อนขั้นตอนการแปลง คุณสามารถลบคุณสมบัติที่กำหนดเองของเอกสาร XLTX ได้ หากต้องการลบคุณสมบัติที่กำหนดเอง ให้เรียกเมธอด [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) และส่งชื่อ คุณสมบัติของเอกสารที่จะลบออก
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xltx-to-pptx/" name="XLTX ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xltx-to-powerpoint/" name="XLTX ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xltx-to-word/" name="XLTX ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xltx-to-wordx/" name="XLTX ถึง WORDX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}