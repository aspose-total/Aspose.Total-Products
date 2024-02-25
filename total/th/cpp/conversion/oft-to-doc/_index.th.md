---
title: ส่งออก OFT เป็น DOC ผ่าน C++
description: C++ API เพื่อแปลง OFT เป็น DOC โดยไม่ต้องใช้ Microsoft Word หรือ Outlook

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: DOC
otherformats: XPS PCL DOTM OTT TIFF MD FLATOPC PDF ODT RTF PS TEXT DOCM BMP SVG EPUB DOCX WORDML EMF DOT GIF JPEG PNG DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อส่งออก OFT ไปยัง DOC" h2="แปลง OFT เป็น DOC ภายในแอปพลิเคชัน C++ โดยไม่ต้องใช้ Microsoft Word หรือ Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณเป็นนักพัฒนา C++ ที่ต้องการเพิ่มคุณสมบัติการแปลงอีเมลในแอปพลิเคชันของคุณหรือไม่? การใช้ [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) คุณสามารถแปลงรูปแบบไฟล์ OFT เป็น HTML ได้ หลังจากนั้น เมื่อใช้ [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API คุณจะสามารถส่งออก HTML ไปยัง DOC ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง OFT เป็น DOC" %}}
1. เปิดไฟล์ OFT โดยใช้ [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message) ข้อมูลอ้างอิง
2. แปลง OFT เป็น HTML โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. โหลด HTML โดยใช้ [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class
4. บันทึกเอกสารในรูปแบบ DOC โดยใช้เมธอด [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) และตั้งค่า Doc เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Doc as save format
doc->Save(u"convertedFile.Doc");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="แยกไฟล์ OFT ผ่าน C++" %}}
ไม่เพียงแต่คุณสามารถแปลง OFT เป็น DOC ได้ แต่คุณยังสามารถอ่าน จัดการ และแยกวิเคราะห์เอกสาร OFT ได้ คุณสามารถรับข้อมูลหัวเรื่อง ที่อยู่ เนื้อหา ผู้รับอีเมลได้โดยใช้คลาส MapiMessage ของ [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) API ตัวอย่างเช่น คุณสามารถตรวจสอบอีเมลผู้ส่งเฉพาะสำหรับการแปลงโดยใช้คุณสมบัติ get_SenderOftAddress()
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderOftAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API เพื่อจำกัดการแก้ไขรูปแบบไฟล์ DOC" %}}
คุณยังสามารถเพิ่มคุณสมบัติการป้องกันเอกสารในแอปของคุณในขณะที่ส่งออกเอกสารจาก OFT ไปยัง DOC การเพิ่มการป้องกันให้กับเอกสารของคุณเป็นขั้นตอนง่ายๆ สิ่งที่คุณต้องทำคือใช้วิธีการป้องกันกับเอกสารของคุณ คุณสามารถตั้งค่าประเภทการป้องกันเป็นอ่านอย่างเดียวเพื่อจำกัดผู้ใช้ในการแก้ไขเอกสาร
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}