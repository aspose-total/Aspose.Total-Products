---
title: แปลง XLTM เป็น POWERPOINT ด้วย .NET 
description: แปลง XLTM เป็น POWERPOINT บน .NET Framework, .NET Core, Mono หรือ Xamarin Platforms

family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: DOCX WORD PPTX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="แปลง XLTM เป็น POWERPOINT ผ่าน C#" h2="ส่งออก Excel&reg; XLTM เป็น POWERPOINT บน .NET Framework, .NET Core, Mono หรือ Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="การแปลง XLTM เป็น POWERPOINT บน .NET" %}}
1. เปิดไฟล์ XLTM โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. แปลง XLTM เป็น PDF และตั้งค่า SaveFormat เป็น Auto
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. บันทึกเอกสารในรูปแบบ POWERPOINT โดยใช้วิธี [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) และตั้งค่า Powerpoint เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code สำหรับการแปลง XLTM เป็น POWERPOINT" gistPath="" %}}
```cs
// load the XLTM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltm");
// save XLTM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/csv-to-word/" name="CSV ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/csv-to-powerpoint/" name="CSV ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/csv-to-pptx/" name="CSV ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/csv-to-docx/" name="CSV ถึง DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}