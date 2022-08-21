---
title: ส่งออก POWERPOINT เป็น DOC บน Andorid ผ่าน Java
description: แปลง POWERPOINT เป็น DOC ในแอพมือถือโดยไม่ต้องติดตั้งซอฟต์แวร์ใดๆ
url: /th/android-java/conversion/powerpoint-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: DOC
otherformats: WORD DOTX DOCM ODT OTT RTF FLATOPC DOTM WORDML DOT TEXT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดง POWERPOINT เป็น DOC บน Andorid ผ่าน Java" h2="รูปแบบไฟล์ API เพื่อแปลง POWERPOINT เป็น DOC ภายในแอป Android โดยไม่ต้องพึ่งพา Microsoft PowerPoint หรือ Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) อนุญาตให้จัดการรูปแบบไฟล์ภายในแอปพลิเคชัน Android ด้วยการใช้ API ที่ให้มาในแพ็คเกจ คุณสามารถทำให้กระบวนการแปลง PowerPoint POWERPOINT เป็น Word DOC ในแอปของคุณเป็นแบบอัตโนมัติ
คุณสามารถแปลงเอกสารที่กำหนดได้ในสองขั้นตอน คุณสามารถใช้ [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) ที่เป็น PowerPoint API สำหรับแอปพลิเคชัน Android เพื่อแสดง POWERPOINT เป็น HTML หลังจากนั้นโดยใช้ API การประมวลผลเอกสาร [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) คุณสามารถแปลง HTML เป็น DOC 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="การแสดงผล POWERPOINT เป็น DOC ใน Android" %}}
1. เปิดไฟล์ POWERPOINT โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง POWERPOINT เป็น HTML โดยใช้ [Save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesISaveOptions-) และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ DOC โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า Doc เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) และ [Aspose.Words สำหรับ Andorid ผ่าน Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ในของคุณ แอปพลิเคชัน

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("input.pptx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Document
Document document = new Document("htmlOutput.html");
// save document in DOC format
document.save("output.doc",SaveFormat.Doc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-word/" name="PPTX ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-dotx/" name="PPTX ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-docm/" name="PPTX ถึง DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-odt/" name="PPTX ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-ott/" name="PPTX ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-rtf/" name="PPTX ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-flatopc/" name="PPTX ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-dotm/" name="PPTX ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-wordml/" name="PPTX ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-dot/" name="PPTX ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-text/" name="PPTX ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptx-to-docx/" name="PPTX ถึง DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}