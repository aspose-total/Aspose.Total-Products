---
title: ส่งออก PPTM เป็น DOTX บน Andorid ผ่าน Java
description: แปลง PPTM เป็น DOTX ในแอพมือถือโดยไม่ต้องติดตั้งซอฟต์แวร์ใดๆ
url: /th/android-java/conversion/pptm-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: DOTX
otherformats: WORDML DOTM FLATOPC DOCX WORD DOT TEXT ODT DOC RTF DOCM OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดง PPTM เป็น DOTX บน Andorid ผ่าน Java" h2="รูปแบบไฟล์ API เพื่อแปลง PPTM เป็น DOTX ภายในแอป Android โดยไม่ต้องพึ่งพา Microsoft PowerPoint หรือ Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ Android ผ่าน Java](https://products.aspose.com/total/android-java/) อนุญาตให้จัดการรูปแบบไฟล์ภายในแอปพลิเคชัน Android ด้วยการใช้ API ที่ให้มาในแพ็คเกจ คุณสามารถทำให้กระบวนการแปลง PowerPoint PPTM เป็น Word DOTX ในแอปของคุณเป็นแบบอัตโนมัติ
คุณสามารถแปลงเอกสารที่กำหนดได้ในสองขั้นตอน คุณสามารถใช้ [Aspose.Slides สำหรับ Andorid ผ่าน Java](https://products.aspose.com/slides/android-java/) ที่เป็น PowerPoint API สำหรับแอปพลิเคชัน Android เพื่อแสดง PPTM เป็น HTML หลังจากนั้นโดยใช้ API การประมวลผลเอกสาร [Aspose.Words สำหรับ Android ผ่าน Java](https://products.aspose.com/words/android-java/) คุณสามารถแปลง HTML เป็น DOTX 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="การแสดงผล PPTM เป็น DOTX ใน Android" %}}
1. เปิดไฟล์ PPTM โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง PPTM เป็น HTML โดยใช้ [บันทึก](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesISaveOptions-) และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้คลาส [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument)
4. บันทึกเอกสารในรูปแบบ DOTX โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int)) และตั้งค่า Dotx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Android ผ่าน Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.Slides สำหรับ Android ผ่าน Java](https://dotxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) และ [Aspose.Words สำหรับ Andorid ผ่าน Java](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ในของคุณ แอปพลิเคชัน

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("input.pptm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotxument
Dotxument dotxument = new Dotxument("htmlOutput.html");
// save dotxument in DOTX format
dotxument.save("output.dotx",SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-wordml/" name="PPTM ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-dotm/" name="PPTM ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-flatopc/" name="PPTM ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-dotxx/" name="PPTM ถึง DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-word/" name="PPTM ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-dot/" name="PPTM ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-text/" name="PPTM ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-odt/" name="PPTM ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-dotx/" name="PPTM ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-rtf/" name="PPTM ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-dotxm/" name="PPTM ถึง DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pptm-to-ott/" name="PPTM ถึง OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}