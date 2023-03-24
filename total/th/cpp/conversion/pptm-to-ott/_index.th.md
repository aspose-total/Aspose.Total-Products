---
title: C++ API เพื่อแปลง PPTM เป็น OTT หรือด้วยตัวแปลงออนไลน์ฟรี
description: ส่งออก PPTM เป็น OTT ภายในแอปพลิเคชัน C++ ของคุณ หรือทางออนไลน์ ทดสอบตัวแปลง POT เป็น CSV ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: OTT
otherformats: DOTM WORDML WORD DOT DOCX ODT RTF DOTX DOCM TEXT DOC FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อแสดงผล PPTM เป็น OTT หรือแอพออนไลน์" h2="ส่งออก PPTM เป็น OTT ในแอปพลิเคชัน C++ โดยไม่ต้องพึ่งพา Microsoft PowerPoint หรือ Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) เป็นแพ็คเกจที่สมบูรณ์ของไลบรารี C++ File Format Automation ด้วยการใช้คุณสมบัติที่หลากหลายของ API ที่มีอยู่ใน pacakge เราสามารถแปลง PowerPoint PPTM เป็น Word OTT ได้อย่างง่ายดาย ในการแปลง คุณสามารถใช้ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API เพื่อแปลง PPTM เป็น HTML ได้ก่อน หลังจากนั้นโดยใช้ API การประมวลผลคำที่มีคุณลักษณะหลากหลาย [Aspose.Words for C++](https://products.aspose.com/words/cpp/) คุณจะสามารถแปลง HTML เป็น OTT ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง PPTM เป็น OTT" %}}
1. โหลดไฟล์ PPTM โดยใช้ [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) การอ้างอิงคลาส
2. แปลง PPTM เป็น HTML โดยใช้ [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) สมาชิก funciton และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้ [Ottument](https://reference.aspose.com/words/cpp/class/aspose.words.ottument) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ OTT โดยใช้ [Save](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_string) ฟังก์ชันสมาชิก
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Ottument
System::SharedPtr<Ottument> ott = System::MakeObject<Ottument>(u"htmlOutput.html");
// save ottument in OTT format
ott->Save(u"output.ott"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ PPTM เป็น OTT</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ott&from=pptm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}