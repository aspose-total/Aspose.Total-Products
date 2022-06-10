---
title: แปลง PPSM เป็น WORDML ผ่าน Java
description: Java API เพื่อส่งออก PPSM เป็น WORDML โดยไม่ต้องใช้ Microsoft Word หรือ PowerPoint
url_ignore: /th/java/conversion/ppsm-to-wordml/
family: total
platformtag: net
feature: conversion
informat: PPSM
outformat: WORDML
otherformats: DOTX DOTM FLATOPC RTF DOT WORDML OTT TEXT WORD ODT WORDMLX WORDMLM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง PPSM เป็น WORDML ผ่าน Java" h2="บน Premise Java API สำหรับการแปลง PowerPoint PPSM เป็น WORDML ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) ไลบรารีระบบอัตโนมัติของรูปแบบไฟล์ช่วยให้นักพัฒนา Java ดำเนินการแปลงเป็นชุดของ PowerPoint PPSM เป็น Word WORDML ได้โดยอัตโนมัติ การแปลงเอกสารเป็นกระบวนการสองขั้นตอนและเกี่ยวข้องกับการใช้สอง API เราจะใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) ซึ่งเป็น PowerPoint API สำหรับการจัดการและจัดการงานนำเสนอเพื่อแปลง PPSM เป็น HTML หลังจากนั้นโดยใช้ API การประมวลผลคำที่มีคุณลักษณะหลากหลาย [Aspose.Words for Java](https://products.aspose.com/words/java/) เราจะแปลง HTML เป็น WORDML
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง PPSM เป็น WORDML ผ่าน Java" %}}
1. เปิดไฟล์ PPSM โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง PPSM เป็น HTML โดยใช้ [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides ISaveOptions-) และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ WORDML โดยใช้วิธีการ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
สำหรับการแปลงไฟล์ PPSM เป็น WORDML คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) ตามโครงการและรวมไลบรารีใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
เมื่อใช้ API คุณยังสามารถทำการแปลงไฟล์ PPSM เป็น WORDML ด้วยลายน้ำ ในการเพิ่มลายน้ำให้กับเอกสาร WORDML ของคุณ ก่อนอื่นให้แปลงไฟล์ PPSM เป็น HTML และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ HTML ที่สร้างขึ้นใหม่โดยใช้คลาส [Wordmlument](https://reference.aspose.com/words/java/com.aspose.words/Wordmlument) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติของมัน วิธี Call Watermark.setText และส่งข้อความลายน้ำ & วัตถุของ TextWatermarkOptions  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-word/" name="PPSM ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-dotx/" name="PPSM ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-odt/" name="PPSM ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-ott/" name="PPSM ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-rtf/" name="PPSM ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-flatopc/" name="PPSM ถึง FLAถึงPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-wordml/" name="PPSM ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-wordmlm/" name="PPSM ถึง WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-text/" name="PPSM ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-wordmlx/" name="PPSM ถึง WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-dotm/" name="PPSM ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsm-to-dot/" name="PPSM ถึง DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}