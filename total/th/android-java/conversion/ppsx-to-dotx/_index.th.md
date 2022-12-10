---
title: ส่งออก PPSX เป็น DOTX บน Andorid ผ่าน Java
description: แปลง PPSX เป็น DOTX ในแอพมือถือโดยไม่ต้องติดตั้งซอฟต์แวร์ใดๆ

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: DOTX
otherformats: WORD DOCX OTT DOC DOT RTF ODT WORDML DOCM FLATOPC DOTM TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดง PPSX เป็น DOTX บน Andorid ผ่าน Java" h2="รูปแบบไฟล์ API เพื่อแปลง PPSX เป็น DOTX ภายในแอป Android โดยไม่ต้องพึ่งพา Microsoft PowerPoint หรือ Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) อนุญาตให้จัดการรูปแบบไฟล์ภายในแอปพลิเคชัน Android ด้วยการใช้ API ที่ให้มาในแพ็คเกจ คุณสามารถทำให้กระบวนการแปลง PowerPoint PPSX เป็น Word DOTX ในแอปของคุณเป็นแบบอัตโนมัติ
คุณสามารถแปลงเอกสารที่กำหนดได้ในสองขั้นตอน คุณสามารถใช้ [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) ที่เป็น PowerPoint API สำหรับแอปพลิเคชัน Android เพื่อแสดง PPSX เป็น HTML หลังจากนั้นโดยใช้ API การประมวลผลเอกสาร [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) คุณสามารถแปลง HTML เป็น DOTX 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="การแสดงผล PPSX เป็น DOTX ใน Android" %}}
1. เปิดไฟล์ PPSX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง PPSX เป็น HTML โดยใช้ [Save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesISaveOptions-) และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้คลาส [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument)
4. บันทึกเอกสารในรูปแบบ DOTX โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int)) และตั้งค่า Dotx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://releases.aspose.com/total/java/) และ ติดตั้ง [Aspose.Slides for Android via Java](https://dotxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) และ [Aspose.Words สำหรับ Andorid ผ่าน Java](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ในของคุณ แอปพลิเคชัน

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("input.ppsx");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-word/" name="PPSX ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-dotxx/" name="PPSX ถึง DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-ott/" name="PPSX ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-dotx/" name="PPSX ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-dot/" name="PPSX ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-rtf/" name="PPSX ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-odt/" name="PPSX ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-wordml/" name="PPSX ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-dotxm/" name="PPSX ถึง DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-flatopc/" name="PPSX ถึง FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-dotm/" name="PPSX ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ppsx-to-text/" name="PPSX ถึง TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}