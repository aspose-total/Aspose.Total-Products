---
title: แสดงผล EMLX เป็น OTT ใน Andorid App
description: ส่งออก EMLX เป็น OTT โดยไม่ต้องใช้ Microsoft Word หรือ Outlook ในแอปพลิเคชัน Andorid ของคุณ

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: OTT
otherformats: GIF MD EPUB BMP FLATOPC DOC EMF PNG SVG TEXT DOTX DOCX TIFF ODT WORDML JPEG PCL XPS PS DOCM PDF DOT RTF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง EMLX เป็น OTT ใน Andorid Apps" h2="การออกแบบแอปพลิเคชัน Andorid เพื่อส่งออก EMLX ไปยัง OTT โดยใช้ Andorid ผ่าน Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
แอพ Andorid ใช้งานง่ายสำหรับผู้ใช้ปลายทางรายวัน จำนวนผู้ใช้โทรศัพท์ Andorid เพิ่มขึ้นทุกวัน การใช้ [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) อันทรงพลังของไลบรารีไฟล์รูปแบบอัตโนมัติทำให้คุณสามารถพัฒนาแอปพลิเคชันการจัดการและแปลงอีเมลได้ คุณสามารถแปลง EMLX เป็น OTT โดยใช้ [Aspose.Emlx สำหรับ Android Java](https://products.aspose.com/emlx/android-java/) และ [Aspose.Words สำหรับ Andorid Java](https://products.aspose.com/words/android-java/) เมื่อใช้ API แรก คุณสามารถแปลงรูปแบบไฟล์ EMLX เป็น HTML และโดยใช้ API ที่สอง คุณสามารถแสดง HTML เป็น OTT 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลง EMLX เป็น OTT ใน Andorid" %}}
1. เปิดไฟล์ EMLX โดยใช้คลาส [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. แปลง EMLX เป็น HTML โดยใช้ [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions) )) กระบวนการ
3. โหลด HTML โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ OTT โดยใช้ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) วิธีการและตั้งค่า OTT เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://releases.aspose.com/total/java/) และ ติดตั้ง [Aspose.Emlx สำหรับ Android ผ่าน Java](https://docs.aspose.com/emlx/androidjava/installation/) และ [Aspose.Words สำหรับ Andorid ผ่าน Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.OTT
document.save("output.ott", SaveFormat.OTT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}