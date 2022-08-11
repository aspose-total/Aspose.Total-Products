---
title: C++ API เพื่อแปลง POTM เป็น TEXT
description: ส่งออก POTM เป็น TEXT ภายในแอปพลิเคชัน C++ ของคุณ
url: /th/cpp/conversion/potm-to-text/
family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: TEXT
otherformats: WORDML DOC DOT DOTX DOCM ODT WORD FLATOPC OTT RTF DOTM DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อแสดงผล POTM เป็น TEXT" h2="ส่งออก POTM เป็น TEXT ในแอปพลิเคชัน C++ โดยไม่ต้องพึ่งพา Microsoft PowerPoint หรือ Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ C++](https://products.aspose.com/total/cpp/) เป็นแพ็คเกจที่สมบูรณ์ของไลบรารี C++ File Format Automation ด้วยการใช้คุณสมบัติที่หลากหลายของ API ที่มีอยู่ใน pacakge เราสามารถแปลง PowerPoint POTM เป็น Word TEXT ได้อย่างง่ายดาย ในการแปลง คุณสามารถใช้ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API เพื่อแปลง POTM เป็น HTML ได้ก่อน หลังจากนั้นโดยใช้ API การประมวลผลคำที่มีคุณลักษณะหลากหลาย [Aspose.Words for C++](https://products.aspose.com/words/cpp/) คุณจะสามารถแปลง HTML เป็น TEXT ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง POTM เป็น TEXT" %}}
1. โหลดไฟล์ POTM โดยใช้ [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) การอ้างอิงคลาส
2. แปลง POTM เป็น HTML โดยใช้ [บันทึก](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) สมาชิก funciton และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้ [Textument](https://reference.aspose.com/words/cpp/class/aspose.words.textument) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ TEXT โดยใช้ [บันทึก](https://reference.aspose.com/words/cpp/class/aspose.words.textument#save_string) ฟังก์ชันสมาชิก
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Textument
System::SharedPtr<Textument> text = System::MakeObject<Textument>(u"htmlOutput.html");
// save textument in TEXT format
text->Save(u"output.text"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-wordml/" name="POTM ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-text/" name="POTM ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-dot/" name="POTM ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-dotx/" name="POTM ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-textm/" name="POTM ถึง TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-odt/" name="POTM ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-word/" name="POTM ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-flatopc/" name="POTM ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-ott/" name="POTM ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-rtf/" name="POTM ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-dotm/" name="POTM ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/potm-to-textx/" name="POTM ถึง TEXTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}