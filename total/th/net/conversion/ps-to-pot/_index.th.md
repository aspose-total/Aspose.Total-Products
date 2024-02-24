---
title: ส่งออก PS เป็น POT ผ่าน C# API
description: .NET API เพื่อแปลง PS เป็น POT โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/net/conversion/ps-to-pot/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: POT
otherformats: POT PPSM PPS SWF XAML POWERPOINT POTX POTM PPSX PPTM PPT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แสดง PS เป็น POT ผ่าน .NET" h2=".NET API เพื่อส่งออก PS เป็น POT บน Windows, macOS และ Linux โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
การใช้แพ็คเกจ File Format Automation API อันทรงพลัง [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถแสดงผล PS เป็น POT ได้อย่างง่ายดายในสองขั้นตอนง่ายๆ เมื่อใช้ PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณจะแปลงรูปแบบไฟล์ PS เป็น PPTX ได้ หลังจากนั้น ด้วยการใช้ Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) คุณจะสามารถแปลง PPTX เป็น POT ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API เพื่อแปลง PS เป็น POT" %}}
1. เปิดไฟล์ PS โดยใช้คลาส [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. แปลง PS เป็น PPTX โดยใช้วิธีการ [บันทึก](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. โหลดไฟล์ PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. บันทึกเอกสารในรูปแบบ POT โดยใช้วิธีการ [บันทึก](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) และตั้งค่า `Pot' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.ps");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.pot", SaveFormat.Pot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับข้อมูลเมตา XMP จากไฟล์ PS ผ่าน .NET" %}}
ขณะแปลง PS เป็น POT คุณอาจต้องการข้อมูลเมตาดาต้า XMP เพิ่มเติมเพื่อจัดลำดับความสำคัญของกระบวนการแปลงแบทช์ของคุณ ตัวอย่างเช่น คุณสามารถรับและจัดเรียงเอกสารการแปลงของคุณตามวันที่สร้างและประมวลผลเอกสารตามนั้น [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ให้คุณเข้าถึงข้อมูลเมตา XMP ของไฟล์ PS หากต้องการรับข้อมูลเมตาของไฟล์ PS ให้สร้างวัตถุ [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) และเปิดไฟล์ PS ที่ป้อนเข้ามา หลังจากนั้น คุณจะรับข้อมูลเมตาของไฟล์ได้โดยใช้คุณสมบัติ [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.ps");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างไฟล์ POT แบบอ่านอย่างเดียวผ่าน .NET" %}}
เมื่อใช้ [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API คุณจะสามารถปรับปรุงคุณลักษณะของแอปพลิเคชันการแปลงของคุณเพิ่มเติมได้ หนึ่งในคุณสมบัติคือสร้างไฟล์เอาต์พุตของคุณแบบอ่านอย่างเดียวเพื่อเพิ่มความปลอดภัย API อนุญาตให้คุณตั้งค่าไฟล์ POT ของคุณเป็นแบบอ่านอย่างเดียว ซึ่งหมายความว่าผู้ใช้ (หลังจากเปิดงานนำเสนอ) จะเห็นคำแนะนำแบบอ่านอย่างเดียว 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pot", SaveFormat.Pot);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}