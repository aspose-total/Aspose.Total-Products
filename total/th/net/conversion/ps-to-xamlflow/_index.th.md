---
title: C# API เพื่อส่งออก PS ไปยัง XAMLFLOW
description: แปลง PS เป็น XAMLFLOW โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/net/conversion/ps-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XAMLFLOW
otherformats: FLATOPC DOTX WORDML MHTML OTT MARKDOWN DOTM ODT PCL DOT RTF XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แสดงผล PS เป็น XAMLFLOW ผ่าน .NET" h2=".NET API เพื่อส่งออก PS เป็น XAMLFLOW บน Windows, macOS และ Linux โดยไม่ต้องใช้ Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) เป็น API ที่มีประสิทธิภาพในการเพิ่มคุณสมบัติการจัดการเอกสารและการแปลงภายในแอปพลิเคชัน .NET ของคุณ ด้วยการใช้ API การประมวลผล PDF ขั้นสูง [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณจะสามารถแปลงรูปแบบไฟล์ PS เป็น DOC ได้ หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for .NET](https://products.aspose.com/words/net/) คุณสามารถแสดง DOC เป็น XAMLFLOW
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API เพื่อแปลง PS เป็น XAMLFLOW" %}}
1. เปิดไฟล์ PS โดยใช้คลาส [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. แปลง PS เป็น Doc โดยใช้วิธีการ [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. โหลดไฟล์ Doc โดยใช้ [Document](https://reference.aspose.com/words/net/aspose.words/document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ XAMLFLOW โดยใช้เมธอด [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) และตั้งค่า Xamlflow เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ถอดรหัสไฟล์ PS โดยใช้รหัสผ่านเจ้าของผ่าน .NET" %}}
ก่อนที่จะแปลง PS เป็น XAMLFLOW หากคุณต้องการถอดรหัสเอกสารของคุณ คุณสามารถทำได้โดยใช้ API ในการถอดรหัสไฟล์ PDF ก่อนอื่นคุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) และเปิด PS โดยใช้รหัสผ่านของเจ้าของ หลังจากนั้น คุณต้องเรียกใช้เมธอด [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) ของออบเจกต์ Document สุดท้าย บันทึกไฟล์ที่อัปเดตโดยใช้วิธีบันทึกของวัตถุเอกสาร  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างไฟล์ XAMLFLOW แบบอ่านอย่างเดียวผ่าน .NET" %}}
เพื่อป้องกัน XAMLFLOW ของคุณจากการแก้ไขและป้องกันไม่ให้ผู้อื่นแก้ไขข้อมูลที่ละเอียดอ่อนและเป็นความลับในเอกสารของคุณ คุณยังสามารถตั้งค่าการป้องกันเอกสารโดยใช้ API ได้อีกด้วย คุณสามารถจำกัดความสามารถในการแก้ไขเอกสารและอนุญาตเฉพาะการดำเนินการบางอย่างกับเอกสารเท่านั้น ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for .NET](https://products.aspose.com/words/net/) ช่วยให้คุณควบคุมวิธีการจำกัดเนื้อหาโดยใช้พารามิเตอร์การแจงนับ [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) คุณสามารถตั้งค่าเอกสารของคุณเป็นแบบอ่านอย่างเดียวโดยใช้รหัสบรรทัดต่อไปนี้ 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xamlflow", SaveFormat.Xamlflow);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}