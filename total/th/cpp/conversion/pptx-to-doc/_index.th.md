---
title: C++ API เพื่อแปลง PPTX เป็น DOC
description: ส่งออก PPTX เป็น DOC ภายในแอปพลิเคชัน C++ ของคุณ
url: /th/cpp/conversion/pptx-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: DOC
otherformats: DOTX DOTM FLATOPC RTF ODT DOT OTT DOCX WORDML DOCM TEXT WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อแสดงผล PPTX เป็น DOC" h2="ส่งออก PPTX เป็น DOC ในแอปพลิเคชัน C++ โดยไม่ต้องพึ่งพา Microsoft PowerPoint หรือ Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ C++](https://products.aspose.com/total/cpp/) เป็นแพ็คเกจที่สมบูรณ์ของไลบรารี C++ File Format Automation ด้วยการใช้คุณสมบัติที่หลากหลายของ API ที่มีอยู่ใน pacakge เราสามารถแปลง PowerPoint PPTX เป็น Word DOC ได้อย่างง่ายดาย ในการแปลง คุณสามารถใช้ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API เพื่อแปลง PPTX เป็น HTML ได้ก่อน หลังจากนั้นโดยใช้ API การประมวลผลคำที่มีคุณลักษณะหลากหลาย [Aspose.Words for C++](https://products.aspose.com/words/cpp/) คุณจะสามารถแปลง HTML เป็น DOC ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง PPTX เป็น DOC" %}}
1. โหลดไฟล์ PPTX โดยใช้ [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) การอ้างอิงคลาส
2. แปลง PPTX เป็น HTML โดยใช้ [บันทึก](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) สมาชิก funciton และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้ [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ DOC โดยใช้ [บันทึก](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string) ฟังก์ชันสมาชิก
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"htmlOutput.html");
// save document in DOC format
doc->Save(u"output.doc"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-dotx/" name="PPTX ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-dotm/" name="PPTX ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-flatopc/" name="PPTX ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-rtf/" name="PPTX ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-odt/" name="PPTX ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-dot/" name="PPTX ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-ott/" name="PPTX ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-docx/" name="PPTX ถึง DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-wordml/" name="PPTX ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-docm/" name="PPTX ถึง DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-text/" name="PPTX ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pptx-to-word/" name="PPTX ถึง WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}