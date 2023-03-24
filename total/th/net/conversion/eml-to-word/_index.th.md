---
title: C# API เพื่อส่งออก EML ไปยัง WORD
description: แปลง EML เป็น WORD โดยไม่ต้องใช้ Microsoft Word หรือ Outlook บน .NET
url_ignore: /th/net/conversion/eml-to-word/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOCX
otherformats: DOC ODT PNG TIFF PDF WORD EMF JPEG TEXT DOT WORDML RTF OTT EPUB MD DOCM DOCX GIF SVG DOTX PCL XPS FLATOPC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก EML เป็น WORD ผ่าน .NET" h2=".NET API เพื่อแสดงผล EML เป็น WORD บน Windows, macOS และ Linux โดยไม่ต้องใช้ Word หรือ Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
หากคุณเป็นนักพัฒนา .NET ที่ต้องการเพิ่มฟีเจอร์การแปลง EML เป็น WORD ภายในแอปพลิเคชันของคุณ [Aspose.Total for .NET](https://products.aspose.com/total/net/) การจัดการรูปแบบไฟล์ API เป็นวิธี ซึ่งไปข้างหน้า. เมื่อใช้ [Aspose.Email for .NET](https://products.aspose.com/email/net/) คุณจะแปลงรูปแบบไฟล์ EML เป็น HTML ได้ หลังจากนั้น คุณสามารถใช้ [Aspose.Words for .NET](https://products.aspose.com/words/net/) เพื่อแสดง HTML เป็น WORD
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API เพื่อแปลง EML เป็น WORD" %}}
1. เปิดไฟล์ EML โดยใช้คลาส [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. แปลง EML เป็น HTML โดยใช้วิธีการ [Save](https://reference.aspose.com/eml/net/aspose.eml.mailmessage/save/methods/3)
3. โหลด HTML โดยใช้คลาส [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. บันทึกเอกสารเป็นรูปแบบ WORD โดยใช้เมธอด [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) และตั้งค่า Word เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="แยกไฟล์ EML ผ่าน .NET" %}}
ก่อนแปลง EML เป็น WORD หากคุณต้องการแน่ใจว่าคุณกำลังแปลงอีเมลที่ถูกต้อง คุณสามารถโหลดเอกสาร EML แยกวิเคราะห์ และดูคุณสมบัติที่คุณต้องการได้ โดยใช้ [MapiMessage](https://reference.aspose.com/eml/net/aspose.eml.mapi/mapimessage) คลาสของ [Aspose.Email for .NET](https://products.aspose.com/eml /net/) API คุณสามารถรับข้อมูลผู้ส่งและผู้รับ ตัวอย่างเช่น คุณสามารถตรวจสอบอีเมลผู้ส่งเฉพาะสำหรับการแปลงโดยใช้คุณสมบัติ [SenderName](https://reference.aspose.com/eml/net/aspose.eml.mapi/mapimessage/properties/sendername)  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
.aspose.com
{{% blocks/products/pf/feature-page-section  h2="จำกัดการแก้ไขเอกสาร WORD ผ่าน .NET" %}}
ขณะบันทึกเอกสารจาก EML เป็น WORD คุณอาจต้องปกป้องเอกสารที่ส่งออกของคุณ บางครั้ง คุณอาจต้องจำกัดความสามารถในการแก้ไขเอกสารและอนุญาตเฉพาะการดำเนินการบางอย่างกับเอกสารเท่านั้น สิ่งนี้มีประโยชน์ในการป้องกันไม่ให้ผู้อื่นแก้ไขข้อมูลที่ละเอียดอ่อนและเป็นความลับในเอกสารของคุณ [Aspose.Words for .NET](https://products.aspose.com/words/net/) API ช่วยให้คุณควบคุมวิธีที่คุณจำกัดเนื้อหาโดยใช้ [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) พารามิเตอร์การแจงนับ คุณสามารถตั้งค่าเอกสารของคุณเป็นแบบอ่านอย่างเดียวโดยใช้รหัสบรรทัดต่อไปนี้ 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}