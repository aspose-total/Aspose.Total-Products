---
title: ส่งออก PDF เป็น XAML ผ่าน C# API
description: .NET API เพื่อแปลง PDF เป็น XAML โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/net/conversion/pdf-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: XAML
otherformats: POWERPOINT POT XAML POTX SWF PPSM PPSX PPT POTM PPS PPTM OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แสดง PDF เป็น XAML ผ่าน .NET" h2=".NET API เพื่อส่งออก PDF เป็น XAML บน Windows, macOS และ Linux โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
การใช้แพ็คเกจ File Format Automation API อันทรงพลัง [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถแสดงผล PDF เป็น XAML ได้อย่างง่ายดายในสองขั้นตอนง่ายๆ เมื่อใช้ PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณจะแปลงรูปแบบไฟล์ PDF เป็น PPTX ได้ หลังจากนั้น ด้วยการใช้ Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) คุณจะสามารถแปลง PPTX เป็น XAML ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API เพื่อแปลง PDF เป็น XAML" %}}
1. เปิดไฟล์ PDF โดยใช้คลาส [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. แปลง PDF เป็น PPTX โดยใช้วิธีการ [บันทึก](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. โหลดไฟล์ PPTX โดยใช้คลาส [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. บันทึกเอกสารในรูปแบบ XAML โดยใช้วิธีการ [บันทึก](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) และตั้งค่า `Xaml' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.pdf");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.xaml", SaveFormat.Xaml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับข้อมูลเมตา XMP จากไฟล์ PDF ผ่าน .NET" %}}
ขณะแปลง PDF เป็น XAML คุณอาจต้องการข้อมูลเมตาดาต้า XMP เพิ่มเติมเพื่อจัดลำดับความสำคัญของกระบวนการแปลงแบทช์ของคุณ ตัวอย่างเช่น คุณสามารถรับและจัดเรียงเอกสารการแปลงของคุณตามวันที่สร้างและประมวลผลเอกสารตามนั้น [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ให้คุณเข้าถึงข้อมูลเมตา XMP ของไฟล์ PDF หากต้องการรับข้อมูลเมตาของไฟล์ PDF ให้สร้างวัตถุ [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) และเปิดไฟล์ PDF ที่ป้อนเข้ามา หลังจากนั้น คุณจะรับข้อมูลเมตาของไฟล์ได้โดยใช้คุณสมบัติ [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.pdf");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างไฟล์ XAML แบบอ่านอย่างเดียวผ่าน .NET" %}}
เมื่อใช้ [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API คุณจะสามารถปรับปรุงคุณลักษณะของแอปพลิเคชันการแปลงของคุณเพิ่มเติมได้ หนึ่งในคุณสมบัติคือสร้างไฟล์เอาต์พุตของคุณแบบอ่านอย่างเดียวเพื่อเพิ่มความปลอดภัย API อนุญาตให้คุณตั้งค่าไฟล์ XAML ของคุณเป็นแบบอ่านอย่างเดียว ซึ่งหมายความว่าผู้ใช้ (หลังจากเปิดงานนำเสนอ) จะเห็นคำแนะนำแบบอ่านอย่างเดียว 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-pot/" name="PDF ถึง POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-ppsx/" name="PDF ถึง PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-swf/" name="PDF ถึง SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-powerpoint/" name="PDF ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-otp/" name="PDF ถึง OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-potm/" name="PDF ถึง POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-ppt/" name="PDF ถึง PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-pps/" name="PDF ถึง PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-potx/" name="PDF ถึง POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-xaml/" name="PDF ถึง XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-ppsm/" name="PDF ถึง PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pdf-to-pptm/" name="PDF ถึง PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}