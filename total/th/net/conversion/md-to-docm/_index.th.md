---
title: C# API เพื่อส่งออก MD ไปยัง DOCM
description: แปลง MD เป็น DOCM โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/net/conversion/md-to-docm/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOCM
otherformats: FLATOPC DOTX ODT XAMLFLOW DOTM RTF DOT MHTML PCL MARKDOWN PS WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แสดงผล MD เป็น DOCM ผ่าน .NET" h2=".NET API เพื่อส่งออก MD เป็น DOCM บน Windows, macOS และ Linux โดยไม่ต้องใช้ Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) เป็น API ที่มีประสิทธิภาพในการเพิ่มคุณสมบัติการจัดการเอกสารและการแปลงภายในแอปพลิเคชัน .NET ของคุณ ด้วยการใช้ API การประมวลผล PDF ขั้นสูง [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณจะสามารถแปลงรูปแบบไฟล์ MD เป็น DOC ได้ หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for .NET](https://products.aspose.com/words/net/) คุณสามารถแสดง DOC เป็น DOCM
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API เพื่อแปลง MD เป็น DOCM" %}}
1. เปิดไฟล์ MD โดยใช้คลาส [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. แปลง MD เป็น Doc โดยใช้วิธีการ [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. โหลดไฟล์ Doc โดยใช้ [Document](https://reference.aspose.com/words/net/aspose.words/document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ DOCM โดยใช้เมธอด [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) และตั้งค่า Docm เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.md");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.docm", SaveFormat.Docm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ถอดรหัสไฟล์ MD โดยใช้รหัสผ่านเจ้าของผ่าน .NET" %}}
ก่อนที่จะแปลง MD เป็น DOCM หากคุณต้องการถอดรหัสเอกสารของคุณ คุณสามารถทำได้โดยใช้ API ในการถอดรหัสไฟล์ PDF ก่อนอื่นคุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) และเปิด MD โดยใช้รหัสผ่านของเจ้าของ หลังจากนั้น คุณต้องเรียกใช้เมธอด [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) ของออบเจกต์ Document สุดท้าย บันทึกไฟล์ที่อัปเดตโดยใช้วิธีบันทึกของวัตถุเอกสาร  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.md", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างไฟล์ DOCM แบบอ่านอย่างเดียวผ่าน .NET" %}}
เพื่อป้องกัน DOCM ของคุณจากการแก้ไขและป้องกันไม่ให้ผู้อื่นแก้ไขข้อมูลที่ละเอียดอ่อนและเป็นความลับในเอกสารของคุณ คุณยังสามารถตั้งค่าการป้องกันเอกสารโดยใช้ API ได้อีกด้วย คุณสามารถจำกัดความสามารถในการแก้ไขเอกสารและอนุญาตเฉพาะการดำเนินการบางอย่างกับเอกสารเท่านั้น ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ช่วยให้คุณควบคุมวิธีการจำกัดเนื้อหาโดยใช้พารามิเตอร์การแจงนับ [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) คุณสามารถตั้งค่าเอกสารของคุณเป็นแบบอ่านอย่างเดียวโดยใช้รหัสบรรทัดต่อไปนี้ 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docm", SaveFormat.Docm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}