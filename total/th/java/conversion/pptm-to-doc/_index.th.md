---
title: แปลง PPTM เป็น DOC ผ่าน Java
description: Java API เพื่อส่งออก PPTM เป็น DOC โดยไม่ต้องใช้ Microsoft Word หรือ PowerPoint
url_ignore: /th/java/conversion/pptm-to-doc/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: DOC
otherformats: DOT FLATOPC TEXT DOTM ODT OTT RTF WORD DOTX DOCX DOCM WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง PPTM เป็น DOC ผ่าน Java" h2="บน Premise Java API สำหรับการแปลง PowerPoint PPTM เป็น DOC ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) ไลบรารีระบบอัตโนมัติของรูปแบบไฟล์ช่วยให้นักพัฒนา Java ดำเนินการแปลงเป็นชุดของ PowerPoint PPTM เป็น Word DOC ได้โดยอัตโนมัติ การแปลงเอกสารเป็นกระบวนการสองขั้นตอนและเกี่ยวข้องกับการใช้สอง API เราจะใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) ซึ่งเป็น PowerPoint API สำหรับการจัดการและจัดการงานนำเสนอเพื่อแปลง PPTM เป็น HTML หลังจากนั้นโดยใช้ API การประมวลผลคำที่มีคุณลักษณะหลากหลาย [Aspose.Words for Java](https://products.aspose.com/words/java/) เราจะแปลง HTML เป็น DOC
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง PPTM เป็น DOC ผ่าน Java" %}}
1. เปิดไฟล์ PPTM โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง PPTM เป็น HTML โดยใช้ [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides ISaveOptions-) และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ DOC โดยใช้วิธีการ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
สำหรับการแปลงไฟล์ PPTM เป็น DOC คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) ตามโครงการและรวมไลบรารีใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
เมื่อใช้ API คุณยังสามารถทำการแปลงไฟล์ PPTM เป็น DOC ด้วยลายน้ำ ในการเพิ่มลายน้ำให้กับเอกสาร DOC ของคุณ ก่อนอื่นให้แปลงไฟล์ PPTM เป็น HTML และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ HTML ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติของมัน วิธี Call Watermark.setText และส่งข้อความลายน้ำ & วัตถุของ TextWatermarkOptions  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-word/" name="PPTM ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-dotx/" name="PPTM ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-odt/" name="PPTM ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-ott/" name="PPTM ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-rtf/" name="PPTM ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-flatopc/" name="PPTM ถึง FLAถึงPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-wordml/" name="PPTM ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-docm/" name="PPTM ถึง DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-text/" name="PPTM ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-docx/" name="PPTM ถึง DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-dotm/" name="PPTM ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptm-to-dot/" name="PPTM ถึง DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}