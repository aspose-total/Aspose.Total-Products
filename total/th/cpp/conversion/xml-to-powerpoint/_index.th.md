---
title: C++ API เพื่อแปลง XML เป็น POWERPOINT
description: แปลง XML เป็น POWERPOINT ผ่าน C++ โดยไม่ต้องใช้ Microsoft Word หรือ Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: POWERPOINT
otherformats: XAML PPT PPTM PPS PPSX POT PPSM POTX POTM OTP SWF ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดงผล XML เป็น POWERPOINT ภายในแอปพลิเคชัน C++" h2="แปลง XML เป็น POWERPOINT ภายในแอปพลิเคชัน C++ ของคุณโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณเป็นนักพัฒนา C++ ที่ต้องการเพิ่มเพื่อรวมคุณลักษณะการแปลง XML เป็น POWERPOINT ภายในแอปพลิเคชัน C++ ของคุณหรือไม่? คุณสามารถทำได้ในสองขั้นตอนง่ายๆ คุณสามารถส่งออก XML เป็น PPTX ได้โดยใช้ [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ประการที่สอง โดยใช้ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) คุณสามารถแปลง PPTX เป็น POWERPOINT API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อส่งออก XML เป็น POWERPOINT" %}}
1. เปิดไฟล์ XML โดยใช้ [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. แปลง XML เป็น PPTX โดยใช้ฟังก์ชันเมธอด [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. โหลดเอกสาร PPTX โดยใช้ [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class reference
4. บันทึกเอกสารในรูปแบบ POWERPOINT โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) และตั้งค่า `Powerpoint' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XML file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xml");
// save XML as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="เปลี่ยนรหัสผ่านของเอกสาร XML ผ่าน C++" %}}
ในกระบวนการแสดง XML เป็น POWERPOINT คุณสามารถเปิด XML ที่ป้องกันด้วยรหัสผ่านและเปลี่ยนรหัสผ่านได้ ในการเปลี่ยนรหัสผ่านของไฟล์ XML คุณต้องทราบรหัสผ่านของเจ้าของเอกสารนั้น คุณสามารถโหลดเอกสาร PDF ที่ป้องกันด้วยรหัสผ่านด้วย [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) โดยระบุรหัสผ่านของเจ้าของและใช้วิธี ChangePasswords เพื่อเปลี่ยนรหัสผ่าน
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XML Document
auto doc = MakeObject<Document>(L"input.xml", L"owner");
// change password of XML Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="เพิ่มรูปภาพจากเว็บในไฟล์ POWERPOINT ผ่าน C++" %}}
หลังจากแปลง XML เป็น POWERPOINT แล้ว คุณยังสามารถเพิ่มรูปภาพจากเว็บไปยังเอกสารเอาต์พุตของคุณได้ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) รองรับการทำงานกับรูปภาพในรูปแบบยอดนิยมเหล่านี้: JPEG, PNG, BMP, GIF และอื่นๆ คุณสามารถเพิ่มหนึ่งภาพหรือหลายภาพบนคอมพิวเตอร์ของคุณลงในสไลด์ในงานนำเสนอได้ โค้ดตัวอย่างในภาษา C++ นี้จะแสดงวิธีเพิ่มรูปภาพลงในไฟล์ POWERPOINT
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POWERPOINT file
auto pres = System::MakeObject<Presentation>("output.powerpoint");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.powerpoint", SaveFormat::Ppt);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}