---
title: แปลง FLATOPC เป็น PPSX ผ่าน C++ หรือด้วยตัวแปลงออนไลน์ฟรี
description: ส่งออก FLATOPC เป็น PPSX ในแอปพลิเคชัน C++ ของคุณโดยไม่ต้องใช้ Microsoft Word ของ PowerPoint หรือทางออนไลน์ ทดสอบตัวแปลง POT เป็น CSV ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด

family: total
platformtag: cpp
feature: conversion
informat: FLATOPC
outformat: PPSX
otherformats: POWERPOINT PPSM PPS PPTM POTX POTM PPTX ODP PPT POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อแปลง FLATOPC เป็น PPSX หรือแอพออนไลน์" h2="ส่งออก FLATOPC เป็น PPSX ภายในแอปพลิเคชัน C++ ของคุณโดยไม่ต้องใช้ Microsoft Word&reg; หรือ PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) ประกอบด้วย API การทำงานอัตโนมัติของไฟล์อันทรงพลังที่อนุญาตให้แปลง FLATOPC เป็น PPSX โดยอัตโนมัติในขณะที่ใช้ API สองตัว โหลด FLATOPC ของคุณโดยใช้ [Aspose.Words for C++](https://products.aspose.com/words/cpp/) แล้วแปลงเป็น HTML จากนั้นโหลด HTML ผ่านการจัดการ PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) เพื่อสร้างงานนำเสนอใหม่และบันทึกเป็น PPSX 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="การแปลง FLATOPC เป็น PPSX บน C++" %}}
1. เปิดไฟล์ FLATOPC โดยใช้ [Flatopcument](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument) การอ้างอิงคลาส
2. แปลง FLATOPC เป็น HTML โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument#save_stdbasicostream_saveoptions)
3. เริ่มต้นวัตถุ [การนำเสนอ](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) ใหม่
4. เพิ่มรูปร่างอัตโนมัติในสไลด์ของคุณ และเพิ่ม AddTextFrame ในนั้น
5. โหลดเนื้อหา HTML และเขียนลงในไฟล์นำเสนอของคุณ
6. บันทึกเอกสารในรูปแบบ PPSX โดยใช้วิธี [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) และตั้งค่า Ppsx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load FLATOPC file with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("template.flatopc");
System::SharedPtr<Flatopcument> flatopc = System::MakeObject<Flatopcument>(u"sourceFile.flatopc");
// save the flatopcument in HTML file format
flatopc->Save(u"HtmlOutput.HTML");
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ FLATOPC เป็น PPSX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ppsx&from=flatopc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="โหลดเอกสาร FLATOPC ที่ป้องกันด้วยรหัสผ่านผ่าน C++" %}}
นอกเหนือจากการแปลงเอกสารแล้ว API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ยังให้ฟีเจอร์การจัดการเอกสารมากมายสำหรับนักพัฒนา C++ ในกรณีที่รูปแบบไฟล์ Microsoft Word FLATOPC ของคุณมีการป้องกันด้วยรหัสผ่าน คุณยังสามารถเปิดไฟล์โดยใช้ API ได้ ในการโหลดเอกสารที่เข้ารหัส คุณสามารถใช้คอนสตรัคเตอร์โอเวอร์โหลดพิเศษ ซึ่งยอมรับอ็อบเจ็กต์ [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) วัตถุนี้มีคุณสมบัติ Password ซึ่งระบุสตริงรหัสผ่าน
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected flatopcument, the password is passed to the flatopcument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"flatopcPassword");
// load the flatopcument from the local file system by filename:
SharedPtr<Flatopcument> flatopc = MakeObject<Flatopcument>(u"Encrypted.flatopc", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="เพิ่มความคิดเห็นในเอกสาร PPSX ผ่าน C++" %}}
ขณะบันทึก FLATOPC เป็น PPSX คุณยังสามารถใช้ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) เพื่อเพิ่มคุณสมบัติเพิ่มเติมในเอกสาร PPSX ของคุณได้ ตัวอย่างเช่น คุณสามารถเพิ่มความคิดเห็นในงานนำเสนอของคุณได้ ข้อคิดเห็นเกี่ยวกับสไลด์การนำเสนอมีความเกี่ยวข้องกับผู้เขียนคนใดคนหนึ่ง คลาสการนำเสนอมีคอลเลกชั่นของผู้เขียนใน ICommentAuthorCollection ซึ่งมีหน้าที่ในการเพิ่มความคิดเห็นเกี่ยวกับสไลด์ สำหรับผู้เขียนแต่ละคน มีชุดความคิดเห็นใน ICommentCollection
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}