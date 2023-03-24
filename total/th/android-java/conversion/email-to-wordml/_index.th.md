---
title: แสดงผล EMAIL เป็น WORDML ใน Andorid App
description: ส่งออก EMAIL เป็น WORDML โดยไม่ต้องใช้ Microsoft Word หรือ Outlook ในแอปพลิเคชัน Andorid ของคุณ

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: WORD_ML
otherformats: DOTX DOC PS DOT EMF XPS TIFF DOCM ODT FLATOPC GIF DOCX PCL RTF PDF DOTM TEXT BMP JPEG OTT SVG MD PNG EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง EMAIL เป็น WORDML ใน Andorid Apps" h2="การออกแบบแอปพลิเคชัน Andorid เพื่อส่งออก EMAIL ไปยัง WORDML โดยใช้ Andorid ผ่าน Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
แอพ Andorid ใช้งานง่ายสำหรับผู้ใช้ปลายทางรายวัน จำนวนผู้ใช้โทรศัพท์ Andorid เพิ่มขึ้นทุกวัน การใช้ [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) อันทรงพลังของไลบรารีไฟล์รูปแบบอัตโนมัติทำให้คุณสามารถพัฒนาแอปพลิเคชันการจัดการและแปลงอีเมลได้ คุณสามารถแปลง EMAIL เป็น WORDML โดยใช้ [Aspose.Email for Android via Java](https://products.aspose.com/email/android-java/) และ [Aspose.Words สำหรับ Andorid Java](https://products.aspose.com/words/android-java/) เมื่อใช้ API แรก คุณสามารถแปลงรูปแบบไฟล์ EMAIL เป็น HTML และโดยใช้ API ที่สอง คุณสามารถแสดง HTML เป็น WORDML 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลง EMAIL เป็น WORDML ใน Andorid" %}}
1. เปิดไฟล์ EMAIL โดยใช้คลาส [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. แปลง EMAIL เป็น HTML โดยใช้ [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions) )) กระบวนการ
3. โหลด HTML โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ WORDML โดยใช้ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) วิธีการและตั้งค่า WORDML เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://releases.aspose.com/total/java/) และ ติดตั้ง [Aspose.Email for Android via Java](https://docs.aspose.com/email/androidjava/installation/) และ [Aspose.Words สำหรับ Andorid ผ่าน Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.WORD_ML
document.save("output.word_ml", SaveFormat.WORD_ML); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}