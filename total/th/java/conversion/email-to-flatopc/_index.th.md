---
title: ส่งออก EMAIL เป็น FLATOPC ผ่าน Java
description: Java API เพื่อแปลง EMAIL เป็น FLATOPC โดยไม่ต้องใช้ Microsoft Word หรือ Outlook
url_ignore: /th/java/conversion/email-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: FLAT_OPC
otherformats: ODT OTT WORDML PS XPS JPEG PCL EMF PNG TEXT EPUB GIF MD DOCX TIFF SVG RTF DOTX FLATOPC DOTM DOC DOT PDF DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อแสดงผล EMAIL เป็น FLATOPC" h2="ส่งออก EMAIL เป็น FLATOPC โดยใช้ Java API ในตัวโดยไม่ต้องใช้การขึ้นต่อกันของบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแปลงอีเมลเป็นคุณสมบัติที่ทรงพลังที่นักพัฒนา Java สามารถรวมเข้ากับแอปพลิเคชัน Java J2SE, J2EE, J2ME ผ่าน [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) ด้วยการใช้สอง API ภายในแพ็คเกจ คุณสามารถแปลง Email EMAIL เป็น FLATOPC โดยไม่ต้องพึ่งพาบุคคลที่สาม ประการแรก คุณสามารถใช้ Email Manipulation API [Aspose.Email for Java](https://products.aspose.com/email/java/) เพื่อแปลงรูปแบบไฟล์ EMAIL เป็น HTML ประการที่สอง คุณสามารถแสดง HTML เป็น FLATOPC โดยใช้ Document Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง EMAIL เป็น FLATOPC" %}}
1. เปิดไฟล์ EMAIL โดยใช้คลาส [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. แปลง EMAIL เป็น HTML โดยใช้ [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) กระบวนการ
3. โหลด HTML โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ FLATOPC โดยใช้ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) วิธีการและตั้งค่า FLATOPC เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณต้องใช้ Aspose.Total สำหรับ Java โดยตรงจากโครงการที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.FLAT_OPC
document.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}