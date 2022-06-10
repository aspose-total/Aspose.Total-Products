---
title: C# API เพื่อส่งออก EPUB ไปยัง MARKDOWN
description: แปลง EPUB เป็น MARKDOWN โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/net/conversion/epub-to-markdown/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: MARKDOWN
otherformats: XAMLFLOW FLATOPC PS MARKDOWN PCL WORDML DOT RTF OTT ODT MHTML DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แสดงผล EPUB เป็น MARKDOWN ผ่าน .NET" h2=".NET API เพื่อส่งออก EPUB เป็น MARKDOWN บน Windows, macOS และ Linux โดยไม่ต้องใช้ Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) เป็น API ที่มีประสิทธิภาพในการเพิ่มคุณสมบัติการจัดการเอกสารและการแปลงภายในแอปพลิเคชัน .NET ของคุณ ด้วยการใช้ API การประมวลผล PDF ขั้นสูง [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณจะสามารถแปลงรูปแบบไฟล์ EPUB เป็น DOC ได้ หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for .NET](https://products.aspose.com/words/net/) คุณสามารถแสดง DOC เป็น MARKDOWN
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API เพื่อแปลง EPUB เป็น MARKDOWN" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. แปลง EPUB เป็น Doc โดยใช้วิธีการ [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. โหลดไฟล์ Doc โดยใช้ [Document](https://reference.aspose.com/words/net/aspose.words/document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ MARKDOWN โดยใช้เมธอด [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) และตั้งค่า Markdown เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.epub");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.markdown", SaveFormat.Markdown);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ถอดรหัสไฟล์ EPUB โดยใช้รหัสผ่านเจ้าของผ่าน .NET" %}}
ก่อนที่จะแปลง EPUB เป็น MARKDOWN หากคุณต้องการถอดรหัสเอกสารของคุณ คุณสามารถทำได้โดยใช้ API ในการถอดรหัสไฟล์ PDF ก่อนอื่นคุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) และเปิด EPUB โดยใช้รหัสผ่านของเจ้าของ หลังจากนั้น คุณต้องเรียกใช้เมธอด [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) ของออบเจกต์ Document สุดท้าย บันทึกไฟล์ที่อัปเดตโดยใช้วิธีบันทึกของวัตถุเอกสาร  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.epub", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างไฟล์ MARKDOWN แบบอ่านอย่างเดียวผ่าน .NET" %}}
เพื่อป้องกัน MARKDOWN ของคุณจากการแก้ไขและป้องกันไม่ให้ผู้อื่นแก้ไขข้อมูลที่ละเอียดอ่อนและเป็นความลับในเอกสารของคุณ คุณยังสามารถตั้งค่าการป้องกันเอกสารโดยใช้ API ได้อีกด้วย คุณสามารถจำกัดความสามารถในการแก้ไขเอกสารและอนุญาตเฉพาะการดำเนินการบางอย่างกับเอกสารเท่านั้น ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ช่วยให้คุณควบคุมวิธีการจำกัดเนื้อหาโดยใช้พารามิเตอร์การแจงนับ [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) คุณสามารถตั้งค่าเอกสารของคุณเป็นแบบอ่านอย่างเดียวโดยใช้รหัสบรรทัดต่อไปนี้ 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.markdown", SaveFormat.Markdown);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-ott/" name="EPUB ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-mhtml/" name="EPUB ถึง MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-wordml/" name="EPUB ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-dot/" name="EPUB ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-odt/" name="EPUB ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-rtf/" name="EPUB ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-ps/" name="EPUB ถึง PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-flatopc/" name="EPUB ถึง FLAถึงPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-pcl/" name="EPUB ถึง PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-markdown/" name="EPUB ถึง MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-xamlflow/" name="EPUB ถึง XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/epub-to-dotx/" name="EPUB ถึง DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}