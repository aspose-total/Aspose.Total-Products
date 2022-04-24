---
title: ส่งออก XML เป็น POT ผ่าน C# API
description: .NET API เพื่อแปลง XML เป็น POT โดยไม่ต้องใช้ Microsoft Word
url: /th/net/conversion/xml-to-pot/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: POT
otherformats: PPS POT XAML POTX SWF PPSM PPT OTP POTM PPTM PPSX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แสดง XML เป็น POT ผ่าน .NET" h2=".NET API เพื่อส่งออก XML เป็น POT บน Windows, macOS และ Linux โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
การใช้แพ็คเกจ File Format Automation API อันทรงพลัง [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถแสดงผล XML เป็น POT ได้อย่างง่ายดายในสองขั้นตอนง่ายๆ เมื่อใช้ PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณจะแปลงรูปแบบไฟล์ XML เป็น PPTX ได้ หลังจากนั้น ด้วยการใช้ Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) คุณจะสามารถแปลง PPTX เป็น POT ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API เพื่อแปลง XML เป็น POT" %}}
1. เปิดไฟล์ XML โดยใช้คลาส [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. แปลง XML เป็น PPTX โดยใช้วิธีการ [บันทึก](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. โหลดไฟล์ PPTX โดยใช้คลาส [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
4. บันทึกเอกสารในรูปแบบ POT โดยใช้วิธีการ [บันทึก](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) และตั้งค่า `Pot' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.xml");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.pot", SaveFormat.Pot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับข้อมูลเมตา XMP จากไฟล์ XML ผ่าน .NET" %}}
ขณะแปลง XML เป็น POT คุณอาจต้องการข้อมูลเมตาดาต้า XMP เพิ่มเติมเพื่อจัดลำดับความสำคัญของกระบวนการแปลงแบทช์ของคุณ ตัวอย่างเช่น คุณสามารถรับและจัดเรียงเอกสารการแปลงของคุณตามวันที่สร้างและประมวลผลเอกสารตามนั้น [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ให้คุณเข้าถึงข้อมูลเมตา XMP ของไฟล์ XML หากต้องการรับข้อมูลเมตาของไฟล์ XML ให้สร้างวัตถุ [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) และเปิดไฟล์ XML ที่ป้อนเข้ามา หลังจากนั้น คุณจะรับข้อมูลเมตาของไฟล์ได้โดยใช้คุณสมบัติ [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document doc = new Document("input.xml");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างไฟล์ POT แบบอ่านอย่างเดียวผ่าน .NET" %}}
เมื่อใช้ [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API คุณจะสามารถปรับปรุงคุณลักษณะของแอปพลิเคชันการแปลงของคุณเพิ่มเติมได้ หนึ่งในคุณสมบัติคือสร้างไฟล์เอาต์พุตของคุณแบบอ่านอย่างเดียวเพื่อเพิ่มความปลอดภัย API อนุญาตให้คุณตั้งค่าไฟล์ POT ของคุณเป็นแบบอ่านอย่างเดียว ซึ่งหมายความว่าผู้ใช้ (หลังจากเปิดงานนำเสนอ) จะเห็นคำแนะนำแบบอ่านอย่างเดียว 
```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pot", SaveFormat.Pot);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-pot/" name="XML ถึง POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-ppsx/" name="XML ถึง PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-swf/" name="XML ถึง SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-powerpoint/" name="XML ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-otp/" name="XML ถึง OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-potm/" name="XML ถึง POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-ppt/" name="XML ถึง PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-pps/" name="XML ถึง PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-potx/" name="XML ถึง POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-xaml/" name="XML ถึง XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-ppsm/" name="XML ถึง PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/xml-to-pptm/" name="XML ถึง PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}