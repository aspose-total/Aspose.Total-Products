---
title: ส่งออก CGM เป็น POTX ผ่าน C# API
description: .NET API เพื่อแปลง CGM เป็น POTX โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/net/conversion/cgm-to-potx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POTX
otherformats: PPTM POTX OTP XAML PPS POT PPT SWF PPSM POTM POWERPOINT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แสดง CGM เป็น POTX ผ่าน .NET" h2=".NET API เพื่อส่งออก CGM เป็น POTX บน Windows, macOS และ Linux โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
การใช้แพ็คเกจ File Format Automation API อันทรงพลัง [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถแสดงผล CGM เป็น POTX ได้อย่างง่ายดายในสองขั้นตอนง่ายๆ เมื่อใช้ PDF Processing API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณจะแปลงรูปแบบไฟล์ CGM เป็น PPTX ได้ หลังจากนั้น ด้วยการใช้ Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) คุณจะสามารถแปลง PPTX เป็น POTX ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API เพื่อแปลง CGM เป็น POTX" %}}
1. เปิดไฟล์ CGM โดยใช้คลาส [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. แปลง CGM เป็น PPTX โดยใช้วิธีการ [บันทึก](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. โหลดไฟล์ PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. บันทึกเอกสารในรูปแบบ POTX โดยใช้วิธีการ [บันทึก](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) และตั้งค่า `Potx' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับข้อมูลเมตา XMP จากไฟล์ CGM ผ่าน .NET" %}}
ขณะแปลง CGM เป็น POTX คุณอาจต้องการข้อมูลเมตาดาต้า XMP เพิ่มเติมเพื่อจัดลำดับความสำคัญของกระบวนการแปลงแบทช์ของคุณ ตัวอย่างเช่น คุณสามารถรับและจัดเรียงเอกสารการแปลงของคุณตามวันที่สร้างและประมวลผลเอกสารตามนั้น [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ให้คุณเข้าถึงข้อมูลเมตา XMP ของไฟล์ CGM หากต้องการรับข้อมูลเมตาของไฟล์ CGM ให้สร้างวัตถุ [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) และเปิดไฟล์ CGM ที่ป้อนเข้ามา หลังจากนั้น คุณจะรับข้อมูลเมตาของไฟล์ได้โดยใช้คุณสมบัติ [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata)  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างไฟล์ POTX แบบอ่านอย่างเดียวผ่าน .NET" %}}
เมื่อใช้ [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API คุณจะสามารถปรับปรุงคุณลักษณะของแอปพลิเคชันการแปลงของคุณเพิ่มเติมได้ หนึ่งในคุณสมบัติคือสร้างไฟล์เอาต์พุตของคุณแบบอ่านอย่างเดียวเพื่อเพิ่มความปลอดภัย API อนุญาตให้คุณตั้งค่าไฟล์ POTX ของคุณเป็นแบบอ่านอย่างเดียว ซึ่งหมายความว่าผู้ใช้ (หลังจากเปิดงานนำเสนอ) จะเห็นคำแนะนำแบบอ่านอย่างเดียว 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potx", SaveFormat.Potx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}