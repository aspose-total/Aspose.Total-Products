---
title: ส่งออก EMLX เป็น WORD ผ่าน C++
description: C++ API เพื่อแปลง EMLX เป็น WORD โดยไม่ต้องใช้ Microsoft Word หรือ Outlook
url: /th/cpp/conversion/emlx-to-word/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOCX
otherformats: DOCM DOCX FLATOPC EPUB DOT TEXT DOTM ODT TIFF EMF DOTX GIF WORDML PDF PNG PS PCL RTF BMP OTT JPEG SVG MD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อส่งออก EMLX ไปยัง WORD" h2="แปลง EMLX เป็น WORD ภายในแอปพลิเคชัน C++ โดยไม่ต้องใช้ Microsoft Word หรือ Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณเป็นนักพัฒนา C++ ที่ต้องการเพิ่มคุณสมบัติการแปลงอีเมลในแอปพลิเคชันของคุณหรือไม่? การใช้ [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) คุณสามารถแปลงรูปแบบไฟล์ EMLX เป็น HTML ได้ หลังจากนั้น เมื่อใช้ [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API คุณจะสามารถส่งออก HTML ไปยัง WORD ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง EMLX เป็น WORD" %}}
1. เปิดไฟล์ EMLX โดยใช้ [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message) ข้อมูลอ้างอิง
2. แปลง EMLX เป็น HTML โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. โหลด HTML โดยใช้ [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class
4. บันทึกเอกสารในรูปแบบ WORD โดยใช้เมธอด [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) และตั้งค่า Word เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Docx as save format
doc->Save(u"convertedFile.Docx");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="แยกไฟล์ EMLX ผ่าน C++" %}}
ไม่เพียงแต่คุณสามารถแปลง EMLX เป็น WORD ได้ แต่คุณยังสามารถอ่าน จัดการ และแยกวิเคราะห์เอกสาร EMLX ได้ คุณสามารถรับข้อมูลหัวเรื่อง ที่อยู่ เนื้อหา ผู้รับอีเมลได้โดยใช้คลาส MapiMessage ของ [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) API ตัวอย่างเช่น คุณสามารถตรวจสอบอีเมลผู้ส่งเฉพาะสำหรับการแปลงโดยใช้คุณสมบัติ get_SenderEmlxAddress()
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.emlx");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlxAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API เพื่อจำกัดการแก้ไขรูปแบบไฟล์ WORD" %}}
คุณยังสามารถเพิ่มคุณสมบัติการป้องกันเอกสารในแอปของคุณในขณะที่ส่งออกเอกสารจาก EMLX ไปยัง WORD การเพิ่มการป้องกันให้กับเอกสารของคุณเป็นขั้นตอนง่ายๆ สิ่งที่คุณต้องทำคือใช้วิธีการป้องกันกับเอกสารของคุณ คุณสามารถตั้งค่าประเภทการป้องกันเป็นอ่านอย่างเดียวเพื่อจำกัดผู้ใช้ในการแก้ไขเอกสาร
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Docx");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-docm/" name="EMLX ถึง DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-docx/" name="EMLX ถึง DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-flatopc/" name="EMLX ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-epub/" name="EMLX ถึง EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-dot/" name="EMLX ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-text/" name="EMLX ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-dotm/" name="EMLX ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-odt/" name="EMLX ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-tiff/" name="EMLX ถึง TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-emf/" name="EMLX ถึง EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-dotx/" name="EMLX ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-gif/" name="EMLX ถึง GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-wordml/" name="EMLX ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-pdf/" name="EMLX ถึง PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-png/" name="EMLX ถึง PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-ps/" name="EMLX ถึง PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-pcl/" name="EMLX ถึง PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-rtf/" name="EMLX ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-word/" name="EMLX ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-ott/" name="EMLX ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-jpeg/" name="EMLX ถึง JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-svg/" name="EMLX ถึง SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-md/" name="EMLX ถึง MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/emlx-to-doc/" name="EMLX ถึง DOC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}