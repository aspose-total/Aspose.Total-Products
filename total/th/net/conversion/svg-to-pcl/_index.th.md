---
title: C# API เพื่อส่งออก SVG ไปยัง PCL
description: แปลง SVG เป็น PCL โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/net/conversion/svg-to-pcl/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: PCL
otherformats: DOTM OTT MHTML DOTX PCL MARKDOWN DOT FLATOPC WORDML ODT PS XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แสดงผล SVG เป็น PCL ผ่าน .NET" h2=".NET API เพื่อส่งออก SVG เป็น PCL บน Windows, macOS และ Linux โดยไม่ต้องใช้ Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) เป็น API ที่มีประสิทธิภาพในการเพิ่มคุณสมบัติการจัดการเอกสารและการแปลงภายในแอปพลิเคชัน .NET ของคุณ ด้วยการใช้ API การประมวลผล PDF ขั้นสูง [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณจะสามารถแปลงรูปแบบไฟล์ SVG เป็น DOC ได้ หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for .NET](https://products.aspose.com/words/net/) คุณสามารถแสดง DOC เป็น PCL
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API เพื่อแปลง SVG เป็น PCL" %}}
1. เปิดไฟล์ SVG โดยใช้คลาส [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. แปลง SVG เป็น Doc โดยใช้วิธีการ [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. โหลดไฟล์ Doc โดยใช้ [Document](https://reference.aspose.com/words/net/aspose.words/document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ PCL โดยใช้เมธอด [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) และตั้งค่า Pcl เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.svg");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.pcl", SaveFormat.Pcl);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ถอดรหัสไฟล์ SVG โดยใช้รหัสผ่านเจ้าของผ่าน .NET" %}}
ก่อนที่จะแปลง SVG เป็น PCL หากคุณต้องการถอดรหัสเอกสารของคุณ คุณสามารถทำได้โดยใช้ API ในการถอดรหัสไฟล์ PDF ก่อนอื่นคุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) และเปิด SVG โดยใช้รหัสผ่านของเจ้าของ หลังจากนั้น คุณต้องเรียกใช้เมธอด [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) ของออบเจกต์ Document สุดท้าย บันทึกไฟล์ที่อัปเดตโดยใช้วิธีบันทึกของวัตถุเอกสาร  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.svg", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างไฟล์ PCL แบบอ่านอย่างเดียวผ่าน .NET" %}}
เพื่อป้องกัน PCL ของคุณจากการแก้ไขและป้องกันไม่ให้ผู้อื่นแก้ไขข้อมูลที่ละเอียดอ่อนและเป็นความลับในเอกสารของคุณ คุณยังสามารถตั้งค่าการป้องกันเอกสารโดยใช้ API ได้อีกด้วย คุณสามารถจำกัดความสามารถในการแก้ไขเอกสารและอนุญาตเฉพาะการดำเนินการบางอย่างกับเอกสารเท่านั้น ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ช่วยให้คุณควบคุมวิธีการจำกัดเนื้อหาโดยใช้พารามิเตอร์การแจงนับ [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) คุณสามารถตั้งค่าเอกสารของคุณเป็นแบบอ่านอย่างเดียวโดยใช้รหัสบรรทัดต่อไปนี้ 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-ott/" name="SVG ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-mhtml/" name="SVG ถึง MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-wordml/" name="SVG ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-dot/" name="SVG ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-odt/" name="SVG ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-rtf/" name="SVG ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-ps/" name="SVG ถึง PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-flatopc/" name="SVG ถึง FLAถึงPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-pcl/" name="SVG ถึง PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-markdown/" name="SVG ถึง MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-xamlflow/" name="SVG ถึง XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-dotx/" name="SVG ถึง DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}