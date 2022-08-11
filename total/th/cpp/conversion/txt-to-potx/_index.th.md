---
title: แปลง TXT เป็น POTX ผ่าน C++
description: ส่งออก TXT เป็น POTX ในแอปพลิเคชัน C++ ของคุณโดยไม่ต้องใช้ Microsoft Word ของ PowerPoint
url: /th/cpp/conversion/txt-to-potx/
family: total
platformtag: cpp
feature: conversion
informat: TXT
outformat: POTX
otherformats: PPTM ODP POWERPOINT PPTX PPS PPSM PPT PPSX POTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อแปลง TXT เป็น POTX" h2="ส่งออก TXT เป็น POTX ภายในแอปพลิเคชัน C++ ของคุณโดยไม่ต้องใช้ Microsoft Word&reg; หรือ PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ C++](https://products.aspose.com/total/cpp/) ประกอบด้วย API การทำงานอัตโนมัติของไฟล์อันทรงพลังที่อนุญาตให้แปลง TXT เป็น POTX โดยอัตโนมัติในขณะที่ใช้ API สองตัว โหลด TXT ของคุณโดยใช้ [Aspose.Words for C++](https://products.aspose.com/words/cpp/) แล้วแปลงเป็น HTML จากนั้นโหลด HTML ผ่านการจัดการ PowerPoint C++ API [Aspose.Slides for C++]( https://products.aspose.com/slides/cpp/) เพื่อสร้างงานนำเสนอใหม่และบันทึกเป็น POTX 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="การแปลง TXT เป็น POTX บน C++" %}}
1. เปิดไฟล์ TXT โดยใช้ [Txtument](https://reference.aspose.com/words/cpp/class/aspose.words.txtument) การอ้างอิงคลาส
2. แปลง TXT เป็น HTML โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/words/cpp/class/aspose.words.txtument#save_stdbasicostream_saveoptions)
3. เริ่มต้นวัตถุ [การนำเสนอ](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) ใหม่
4. เพิ่มรูปร่างอัตโนมัติในสไลด์ของคุณ และเพิ่ม AddTextFrame ในนั้น
5. โหลดเนื้อหา HTML และเขียนลงในไฟล์นำเสนอของคุณ
6. บันทึกเอกสารในรูปแบบ POTX โดยใช้วิธี [บันทึก](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) และตั้งค่า Potx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TXT file with an instance of Txtument
Txtument txtument = new Txtument("template.txt");
System::SharedPtr<Txtument> txt = System::MakeObject<Txtument>(u"sourceFile.txt");
// save the txtument in HTML file format
txt->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);                  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="โหลดเอกสาร TXT ที่ป้องกันด้วยรหัสผ่านผ่าน C++" %}}
นอกเหนือจากการแปลงเอกสารแล้ว API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ยังให้ฟีเจอร์การจัดการเอกสารมากมายสำหรับนักพัฒนา C++ ในกรณีที่รูปแบบไฟล์ Microsoft Word TXT ของคุณมีการป้องกันด้วยรหัสผ่าน คุณยังสามารถเปิดไฟล์โดยใช้ API ได้ ในการโหลดเอกสารที่เข้ารหัส คุณสามารถใช้คอนสตรัคเตอร์โอเวอร์โหลดพิเศษ ซึ่งยอมรับอ็อบเจ็กต์ [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) วัตถุนี้มีคุณสมบัติ Password ซึ่งระบุสตริงรหัสผ่าน
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected txtument, the password is passed to the txtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"txtPassword");
// load the txtument from the local file system by filename:
SharedPtr<Txtument> txt = MakeObject<Txtument>(u"Encrypted.txt", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="เพิ่มความคิดเห็นในเอกสาร POTX ผ่าน C++" %}}
ขณะบันทึก TXT เป็น POTX คุณยังสามารถใช้ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) เพื่อเพิ่มคุณสมบัติเพิ่มเติมในเอกสาร POTX ของคุณได้ ตัวอย่างเช่น คุณสามารถเพิ่มความคิดเห็นในงานนำเสนอของคุณได้ ข้อคิดเห็นเกี่ยวกับสไลด์การนำเสนอมีความเกี่ยวข้องกับผู้เขียนคนใดคนหนึ่ง คลาสการนำเสนอมีคอลเลกชั่นของผู้เขียนใน ICommentAuthorCollection ซึ่งมีหน้าที่ในการเพิ่มความคิดเห็นเกี่ยวกับสไลด์ สำหรับผู้เขียนแต่ละคน มีชุดความคิดเห็นใน ICommentCollection
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/txt-to-pptm/" name="TXT ถึง PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/txt-to-potx/" name="TXT ถึง POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/txt-to-powerpoint/" name="TXT ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/txt-to-pptx/" name="TXT ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/txt-to-pps/" name="TXT ถึง PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/txt-to-ppsm/" name="TXT ถึง PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/txt-to-ppt/" name="TXT ถึง PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/txt-to-ppsx/" name="TXT ถึง PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/txt-to-potm/" name="TXT ถึง POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/txt-to-pot/" name="TXT ถึง POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}