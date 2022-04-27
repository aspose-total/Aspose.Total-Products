---
title: C# API เพื่อส่งออก MSG ไปยัง DOTM
description: แปลง MSG เป็น DOTM โดยไม่ต้องใช้ Microsoft Word หรือ Outlook บน .NET
url: /th/net/conversion/msg-to-dotm/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOTM
otherformats: DOC OTT EPUB JPEG WORDML FLATOPC PDF EMF TIFF DOT ODT DOCM GIF XPS TEXT PNG DOCX PS PCL DOTX DOTM MD SVG RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ส่งออก MSG เป็น DOTM ผ่าน .NET" h2=".NET API เพื่อแสดงผล MSG เป็น DOTM บน Windows, macOS และ Linux โดยไม่ต้องใช้ Word หรือ Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
หากคุณเป็นนักพัฒนา .NET ที่ต้องการเพิ่มฟีเจอร์การแปลง MSG เป็น DOTM ภายในแอปพลิเคชันของคุณ [Aspose.Total for .NET](https://products.aspose.com/total/net/) การจัดการรูปแบบไฟล์ API เป็นวิธี ซึ่งไปข้างหน้า. เมื่อใช้ [Aspose.Msg for .NET](https://products.aspose.com/msg/net/) คุณจะแปลงรูปแบบไฟล์ MSG เป็น HTML ได้ หลังจากนั้น คุณสามารถใช้ [Aspose.Words for .NET](https://products.aspose.com/words/net/) เพื่อแสดง HTML เป็น DOTM
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API เพื่อแปลง MSG เป็น DOTM" %}}
1. เปิดไฟล์ MSG โดยใช้คลาส [MailMessage](https://apireference.aspose.com/msg/net/aspose.msg/mailmessage)
2. แปลง MSG เป็น HTML โดยใช้วิธีการ [Save](https://apireference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. โหลด HTML โดยใช้คลาส [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. บันทึกเอกสารเป็นรูปแบบ DOTM โดยใช้เมธอด [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) และตั้งค่า Dotm เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.dotm", SaveFormat.Dotm); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="แยกไฟล์ MSG ผ่าน .NET" %}}
ก่อนแปลง MSG เป็น DOTM หากคุณต้องการแน่ใจว่าคุณกำลังแปลงอีเมลที่ถูกต้อง คุณสามารถโหลดเอกสาร MSG แยกวิเคราะห์ และดูคุณสมบัติที่คุณต้องการได้ โดยใช้ [MapiMessage](https://apireference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) คลาสของ [Aspose.Msg for .NET](https://products.aspose.com/msg /net/) API คุณสามารถรับข้อมูลผู้ส่งและผู้รับ ตัวอย่างเช่น คุณสามารถตรวจสอบอีเมลผู้ส่งเฉพาะสำหรับการแปลงโดยใช้คุณสมบัติ [SenderName](https://apireference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername)  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
.aspose.com
{{% blocks/products/pf/feature-page-section  h2="จำกัดการแก้ไขเอกสาร DOTM ผ่าน .NET" %}}
ขณะบันทึกเอกสารจาก MSG เป็น DOTM คุณอาจต้องปกป้องเอกสารที่ส่งออกของคุณ บางครั้ง คุณอาจต้องจำกัดความสามารถในการแก้ไขเอกสารและอนุญาตเฉพาะการดำเนินการบางอย่างกับเอกสารเท่านั้น สิ่งนี้มีประโยชน์ในการป้องกันไม่ให้ผู้อื่นแก้ไขข้อมูลที่ละเอียดอ่อนและเป็นความลับในเอกสารของคุณ [Aspose.Words for .NET](https://products.aspose.com/words/net/) API ช่วยให้คุณควบคุมวิธีที่คุณจำกัดเนื้อหาโดยใช้ [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) พารามิเตอร์การแจงนับ คุณสามารถตั้งค่าเอกสารของคุณเป็นแบบอ่านอย่างเดียวโดยใช้รหัสบรรทัดต่อไปนี้ 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotm", SaveFormat.Dotm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-pcl/" name="ผงชูรส TO PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-pdf/" name="ผงชูรส TO PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-dot/" name="ผงชูรส TO DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-flatopc/" name="ผงชูรสเพื่อ FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-jpeg/" name="ผงชูรสเป็น JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-png/" name="ผงชูรสเป็น PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-rtf/" name="ผงชูรสเป็น RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-tiff/" name="ผงชูรสถึง TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-docm/" name="ผงชูรส TO DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-ps/" name="ผงชูรสเพื่อ PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-gif/" name="ผงชูรสถึง GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-xps/" name="ผงชูรสเป็น XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-odt/" name="ผงชูรสเป็น ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-docx/" name="ผงชูรส TO DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-doc/" name="ผงชูรสถึงเอกสาร" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-wordml/" name="ผงชูรสเป็น WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-svg/" name="ผงชูรสเป็น SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-epub/" name="ผงชูรสถึง EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-md/" name="ผงชูรส TO MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-emf/" name="ผงชูรสถึง EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-dotm/" name="ผงชูรส TO DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-ott/" name="ผงชูรส TO OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-dotx/" name="ผงชูรสเป็น DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/msg-to-text/" name="ผงชูรสเป็นข้อความ" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}