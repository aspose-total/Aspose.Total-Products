---
title: C# API เพื่อส่งออก EMAIL ไปยัง EPUB
description: แปลง EMAIL เป็น EPUB โดยไม่ต้องใช้ Microsoft Word หรือ Outlook บน .NET
url_ignore: /th/net/conversion/email-to-epub/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EPUB
otherformats: DOTM PNG PS SVG TIFF JPEG ODT DOT DOCM PCL OTT EPUB WORDML DOTX RTF MD PDF GIF FLATOPC EMF TEXT XPS DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก EMAIL เป็น EPUB ผ่าน .NET" h2=".NET API เพื่อแสดงผล EMAIL เป็น EPUB บน Windows, macOS และ Linux โดยไม่ต้องใช้ Word หรือ Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
หากคุณเป็นนักพัฒนา .NET ที่ต้องการเพิ่มฟีเจอร์การแปลง EMAIL เป็น EPUB ภายในแอปพลิเคชันของคุณ [Aspose.Total for .NET](https://products.aspose.com/total/net/) การจัดการรูปแบบไฟล์ API เป็นวิธี ซึ่งไปข้างหน้า. เมื่อใช้ [Aspose.Email for .NET](https://products.aspose.com/email/net/) คุณจะแปลงรูปแบบไฟล์ EMAIL เป็น HTML ได้ หลังจากนั้น คุณสามารถใช้ [Aspose.Words for .NET](https://products.aspose.com/words/net/) เพื่อแสดง HTML เป็น EPUB
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API เพื่อแปลง EMAIL เป็น EPUB" %}}
1. เปิดไฟล์ EMAIL โดยใช้คลาส [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. แปลง EMAIL เป็น HTML โดยใช้วิธีการ [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. โหลด HTML โดยใช้คลาส [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. บันทึกเอกสารเป็นรูปแบบ EPUB โดยใช้เมธอด [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) และตั้งค่า Epub เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="แยกไฟล์ EMAIL ผ่าน .NET" %}}
ก่อนแปลง EMAIL เป็น EPUB หากคุณต้องการแน่ใจว่าคุณกำลังแปลงอีเมลที่ถูกต้อง คุณสามารถโหลดเอกสาร EMAIL แยกวิเคราะห์ และดูคุณสมบัติที่คุณต้องการได้ โดยใช้ [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) คลาสของ [Aspose.Email for .NET](https://products.aspose.com/email /net/) API คุณสามารถรับข้อมูลผู้ส่งและผู้รับ ตัวอย่างเช่น คุณสามารถตรวจสอบอีเมลผู้ส่งเฉพาะสำหรับการแปลงโดยใช้คุณสมบัติ [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername)  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="จำกัดการแก้ไขเอกสาร EPUB ผ่าน .NET" %}}
ขณะบันทึกเอกสารจาก EMAIL เป็น EPUB คุณอาจต้องปกป้องเอกสารที่ส่งออกของคุณ บางครั้ง คุณอาจต้องจำกัดความสามารถในการแก้ไขเอกสารและอนุญาตเฉพาะการดำเนินการบางอย่างกับเอกสารเท่านั้น สิ่งนี้มีประโยชน์ในการป้องกันไม่ให้ผู้อื่นแก้ไขข้อมูลที่ละเอียดอ่อนและเป็นความลับในเอกสารของคุณ [Aspose.Words for .NET](https://products.aspose.com/words/net/) API ช่วยให้คุณควบคุมวิธีที่คุณจำกัดเนื้อหาโดยใช้ [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) พารามิเตอร์การแจงนับ คุณสามารถตั้งค่าเอกสารของคุณเป็นแบบอ่านอย่างเดียวโดยใช้รหัสบรรทัดต่อไปนี้ 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}