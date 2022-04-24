---
title: แปลง PPSX เป็น DOCX ผ่าน Java
description: Java API เพื่อส่งออก PPSX เป็น DOCX โดยไม่ต้องใช้ Microsoft Word หรือ PowerPoint
url: /th/java/conversion/ppsx-to-docx/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: DOCXX
otherformats: RTF DOCX DOTM OTT WORD WORDML DOTX FLATOPC DOT TEXT ODT DOCXM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง PPSX เป็น DOCX ผ่าน Java" h2="บน Premise Java API สำหรับการแปลง PowerPoint PPSX เป็น DOCX ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) ไลบรารีระบบอัตโนมัติของรูปแบบไฟล์ช่วยให้นักพัฒนา Java ดำเนินการแปลงเป็นชุดของ PowerPoint PPSX เป็น Word DOCX ได้โดยอัตโนมัติ การแปลงเอกสารเป็นกระบวนการสองขั้นตอนและเกี่ยวข้องกับการใช้สอง API เราจะใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) ซึ่งเป็น PowerPoint API สำหรับการจัดการและจัดการงานนำเสนอเพื่อแปลง PPSX เป็น HTML หลังจากนั้นโดยใช้ API การประมวลผลคำที่มีคุณลักษณะหลากหลาย [Aspose.Words for Java](https://products.aspose.com/words/java/) เราจะแปลง HTML เป็น DOCX
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง PPSX เป็น DOCX ผ่าน Java" %}}
1. เปิดไฟล์ PPSX โดยใช้คลาส [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง PPSX เป็น HTML โดยใช้ [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides ISaveOptions-) และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้คลาส [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ DOCX โดยใช้วิธีการ [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
สำหรับการแปลงไฟล์ PPSX เป็น DOCX คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose /aspose-total) ตามโครงการและรวมไลบรารีใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}[Document]
เมื่อใช้ API คุณยังสามารถทำการแปลงไฟล์ PPSX เป็น DOCX ด้วยลายน้ำ ในการเพิ่มลายน้ำให้กับเอกสาร DOCX ของคุณ ก่อนอื่นให้แปลงไฟล์ PPSX เป็น HTML และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ HTML ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติของมัน วิธี Call Watermark.setText และส่งข้อความลายน้ำ & วัตถุของ TextWatermarkOptions  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-word/" name="PPSX ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-dotx/" name="PPSX ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-odt/" name="PPSX ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-ott/" name="PPSX ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-rtf/" name="PPSX ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-flatopc/" name="PPSX ถึง FLAถึงPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-wordml/" name="PPSX ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-docxm/" name="PPSX ถึง DOCXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-text/" name="PPSX ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-docxx/" name="PPSX ถึง DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-dotm/" name="PPSX ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ppsx-to-dot/" name="PPSX ถึง DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}