---
title: C++ API เพื่อแปลง PPS เป็น WORDML
description: ส่งออก PPS เป็น WORDML ภายในแอปพลิเคชัน C++ ของคุณ

family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: WORDML
otherformats: DOTM DOCX DOCM WORD DOTX RTF TEXT OTT DOT FLATOPC ODT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อแสดงผล PPS เป็น WORDML" h2="ส่งออก PPS เป็น WORDML ในแอปพลิเคชัน C++ โดยไม่ต้องพึ่งพา Microsoft PowerPoint หรือ Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) เป็นแพ็คเกจที่สมบูรณ์ของไลบรารี C++ File Format Automation ด้วยการใช้คุณสมบัติที่หลากหลายของ API ที่มีอยู่ใน pacakge เราสามารถแปลง PowerPoint PPS เป็น Word WORDML ได้อย่างง่ายดาย ในการแปลง คุณสามารถใช้ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API เพื่อแปลง PPS เป็น HTML ได้ก่อน หลังจากนั้นโดยใช้ API การประมวลผลคำที่มีคุณลักษณะหลากหลาย [Aspose.Words for C++](https://products.aspose.com/words/cpp/) คุณจะสามารถแปลง HTML เป็น WORDML ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง PPS เป็น WORDML" %}}
1. โหลดไฟล์ PPS โดยใช้ [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) การอ้างอิงคลาส
2. แปลง PPS เป็น HTML โดยใช้ [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) สมาชิก funciton และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้ [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ WORDML โดยใช้ [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string) ฟังก์ชันสมาชิก
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPS file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pps");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Wordmlument
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"htmlOutput.html");
// save wordmlument in WORDML format
wordml->Save(u"output.wordml"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-dotm/" name="PPS ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-wordmlx/" name="PPS ถึง WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-wordmlm/" name="PPS ถึง WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-word/" name="PPS ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-dotx/" name="PPS ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-rtf/" name="PPS ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-text/" name="PPS ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-ott/" name="PPS ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-dot/" name="PPS ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-flatopc/" name="PPS ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-odt/" name="PPS ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/pps-to-wordml/" name="PPS ถึง WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}