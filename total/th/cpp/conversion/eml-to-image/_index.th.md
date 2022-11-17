---
title: ส่งออก EML เป็น IMAGE ผ่าน C++
description: C++ API เพื่อแปลง EML เป็น IMAGE โดยไม่ต้องใช้ Microsoft Word หรือ Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: PNG
otherformats: XPS FLATOPC DOTM TIFF JPEG EPUB DOCX WORDML DOCM MD PDF OTT PS BMP PCL DOT SVG GIF ODT EMF PNG TEXT RTF DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อส่งออก EML ไปยัง IMAGE" h2="แปลง EML เป็น IMAGE ภายในแอปพลิเคชัน C++ โดยไม่ต้องใช้ Microsoft Word หรือ Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณเป็นนักพัฒนา C++ ที่ต้องการเพิ่มคุณสมบัติการแปลงอีเมลในแอปพลิเคชันของคุณหรือไม่? การใช้ [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) คุณสามารถแปลงรูปแบบไฟล์ EML เป็น HTML ได้ หลังจากนั้น เมื่อใช้ [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API คุณจะสามารถส่งออก HTML ไปยัง IMAGE ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง EML เป็น IMAGE" %}}
1. เปิดไฟล์ EML โดยใช้ [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message) ข้อมูลอ้างอิง
2. แปลง EML เป็น HTML โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. โหลด HTML โดยใช้ [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class
4. บันทึกเอกสารในรูปแบบ IMAGE โดยใช้เมธอด [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) และตั้งค่า Image เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="แยกไฟล์ EML ผ่าน C++" %}}
ไม่เพียงแต่คุณสามารถแปลง EML เป็น IMAGE ได้ แต่คุณยังสามารถอ่าน จัดการ และแยกวิเคราะห์เอกสาร EML ได้ คุณสามารถรับข้อมูลหัวเรื่อง ที่อยู่ เนื้อหา ผู้รับอีเมลได้โดยใช้คลาส MapiMessage ของ [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API ตัวอย่างเช่น คุณสามารถตรวจสอบอีเมลผู้ส่งเฉพาะสำหรับการแปลงโดยใช้คุณสมบัติ get_SenderEmlAddress()
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API เพื่อจำกัดการแก้ไขรูปแบบไฟล์ IMAGE" %}}
คุณยังสามารถเพิ่มคุณสมบัติการป้องกันเอกสารในแอปของคุณในขณะที่ส่งออกเอกสารจาก EML ไปยัง IMAGE การเพิ่มการป้องกันให้กับเอกสารของคุณเป็นขั้นตอนง่ายๆ สิ่งที่คุณต้องทำคือใช้วิธีการป้องกันกับเอกสารของคุณ คุณสามารถตั้งค่าประเภทการป้องกันเป็นอ่านอย่างเดียวเพื่อจำกัดผู้ใช้ในการแก้ไขเอกสาร
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Png");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-xps/" name="EML ถึง XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-flatopc/" name="EML ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-dotm/" name="EML ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-tiff/" name="EML ถึง TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-jpeg/" name="EML ถึง JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-epub/" name="EML ถึง EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-docx/" name="EML ถึง DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-wordml/" name="EML ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-docm/" name="EML ถึง DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-md/" name="EML ถึง MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-pdf/" name="EML ถึง PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-ott/" name="EML ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-ps/" name="EML ถึง PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-image/" name="EML ถึง IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-pcl/" name="EML ถึง PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-dot/" name="EML ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-svg/" name="EML ถึง SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-gif/" name="EML ถึง GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-odt/" name="EML ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-emf/" name="EML ถึง EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-png/" name="EML ถึง PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-text/" name="EML ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-rtf/" name="EML ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/eml-to-dotx/" name="EML ถึง DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}