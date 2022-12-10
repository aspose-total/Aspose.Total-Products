---
title: ส่งออก XLT เป็น PPTX ใน Android
description: Android API เพื่อแปลง XLT เป็น PPTX โดยไม่ต้องใช้ Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: PPTX
otherformats: DOC DOCX WORD POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดงผล XLT เป็น PPTX บน Android ผ่าน Java" h2="แปลง XLT เป็น PPTX ภายในแอปพลิเคชัน Android ของคุณโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) เป็นแพ็คเกจของ File Automation API ที่ทรงพลัง ด้วยการใช้ API สองอัน คุณสามารถรวมคุณลักษณะการแปลง XLT เป็น PPTX ในแอปพลิเคชัน Android ของคุณได้ ในขั้นตอนแรก คุณสามารถส่งออก XLT เป็น PDF ได้โดยใช้ [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) หลังจากนั้น ด้วยการใช้ [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) คุณจะสามารถแปลง PDF เป็น PPTX ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อส่งออก XLT เป็น PPTX" %}}
1. เปิดไฟล์ XLT โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. แปลง XLT เป็น PDF และตั้งค่า SaveFormat เป็น AUTO
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. บันทึกเอกสารในรูปแบบ PPTX โดยใช้ [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.PDF for Android via Java](https://pptxs.aspose.com/pdf/androidjava/installation/) และ [Aspose.Cells for Android via Java](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// save XLT as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ลบคุณสมบัติที่กำหนดเองออกจากไฟล์ XLT ใน Android ผ่าน Java" %}}
นอกจากการแปลงเอกสารแล้ว [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) ยังมีฟีเจอร์อื่นๆ อีกเป็นจำนวนมากอีกด้วย ก่อนขั้นตอนการแปลง คุณสามารถลบคุณสมบัติที่กำหนดเองของเอกสาร XLT ได้ หากต้องการลบคุณสมบัติที่กำหนดเอง ให้เรียกเมธอด [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) และส่งชื่อ คุณสมบัติของเอกสารที่จะลบออก
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xlt-to-pptx/" name="XLT ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xlt-to-pptxx/" name="XLT ถึง PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xlt-to-word/" name="XLT ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xlt-to-powerpoint/" name="XLT ถึง POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}