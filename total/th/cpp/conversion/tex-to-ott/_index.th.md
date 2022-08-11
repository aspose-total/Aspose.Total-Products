---
title: C++ API เพื่อส่งออก TEX ไปยัง OTT
description: แปลง TEX เป็น OTT ภายในแอปพลิเคชัน C++
url: /th/cpp/conversion/tex-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: OTT
otherformats: MARKDOWN RTF DOTX PS FLATOPC DOCM PCL MHTML ODT DOT XAMLFLOW WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อส่งออก TEX ไปยัง OTT" h2="แสดงผล TEX เป็น OTT ภายในแอปพลิเคชัน C++ โดยไม่ต้องใช้แอปพลิเคชันของบุคคลที่สาม" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ C++](https://products.aspose.com/total/cpp/) ไลบรารีรูปแบบไฟล์อัตโนมัติช่วยให้นักพัฒนา C++ สามารถแปลง TEX เป็น OTT ในสองขั้นตอนง่ายๆ ประการแรก คุณสามารถใช้ [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API เพื่อแปลงรูปแบบไฟล์ TEX เป็น DOC ประการที่สอง โดยใช้ API การประมวลผลเอกสาร Word ขั้นสูง [Aspose.Words for C++](https://products.aspose.com/words/cpp/) คุณสามารถส่งออก DOC ไปยัง OTT 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแสดงผล TEX เป็น OTT" %}}
1. เปิดไฟล์ TEX โดยใช้ [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. แปลง TEX เป็น DOC โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference ของ Aspose.Words API
4. บันทึกเอกสารในรูปแบบ OTT โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TEX file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.tex");
// save TEX as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Ott
wordDoc->Save(u"output.Ott");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="เปลี่ยนรหัสผ่านของเอกสาร TEX ผ่าน C++" %}}
ในกระบวนการแสดงผล TEX เป็น OTT คุณสามารถเปิด TEX ที่ป้องกันด้วยรหัสผ่านและเปลี่ยนรหัสผ่านได้ ในการเปลี่ยนรหัสผ่านของไฟล์ TEX คุณต้องทราบรหัสผ่านของเจ้าของเอกสารนั้น คุณสามารถโหลดเอกสาร PDF ที่ป้องกันด้วยรหัสผ่านด้วย [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) โดยระบุรหัสผ่านของเจ้าของและใช้วิธี ChangePasswords เพื่อเปลี่ยนรหัสผ่าน
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing TEX Document
auto doc = MakeObject<Document>(L"input.tex", L"owner");
// change password of TEX Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="จำกัดการแก้ไขไฟล์ OTT ผ่าน C++" %}}
คุณยังจำกัดการแก้ไขไฟล์ OTT ได้โดยใช้ API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) บางครั้ง คุณอาจต้องจำกัดความสามารถในการแก้ไขเอกสารและอนุญาตเฉพาะการดำเนินการบางอย่างกับเอกสารเท่านั้น API ช่วยให้คุณควบคุมวิธีการจำกัดเนื้อหาโดยใช้พารามิเตอร์การแจงนับ [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) ตัวอย่างโค้ดต่อไปนี้สาธิตวิธีจำกัดการแก้ไขในเอกสาร จึงสามารถแก้ไขได้เฉพาะในช่องแบบฟอร์มเท่านั้น
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Ott");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-markdown/" name="TEX ถึง MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-rtf/" name="TEX ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-dotx/" name="TEX ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-ps/" name="TEX ถึง PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-flatopc/" name="TEX ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-ott/" name="TEX ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-pcl/" name="TEX ถึง PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-mhtml/" name="TEX ถึง MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-odt/" name="TEX ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-dot/" name="TEX ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-xamlflow/" name="TEX ถึง XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-wordml/" name="TEX ถึง WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}