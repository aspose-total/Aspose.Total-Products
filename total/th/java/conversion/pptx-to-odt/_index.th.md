---
title: แปลง PPTX เป็น ODT ผ่าน Java
description: Java API เพื่อส่งออก PPTX เป็น ODT โดยไม่ต้องใช้ Microsoft Word หรือ PowerPoint
url_ignore: /th/java/conversion/pptx-to-odt/
family: total
platformtag: net
feature: conversion
informat: PPTX
outformat: ODT
otherformats: ODTX OTT TEXT ODT DOT DOTX ODTM WORD FLATOPC WORDML RTF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง PPTX เป็น ODT ผ่าน Java" h2="บน Premise Java API สำหรับการแปลง PowerPoint PPTX เป็น ODT ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) ไลบรารีระบบอัตโนมัติของรูปแบบไฟล์ช่วยให้นักพัฒนา Java ดำเนินการแปลงเป็นชุดของ PowerPoint PPTX เป็น Word ODT ได้โดยอัตโนมัติ การแปลงเอกสารเป็นกระบวนการสองขั้นตอนและเกี่ยวข้องกับการใช้สอง API เราจะใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) ซึ่งเป็น PowerPoint API สำหรับการจัดการและจัดการงานนำเสนอเพื่อแปลง PPTX เป็น HTML หลังจากนั้นโดยใช้ API การประมวลผลคำที่มีคุณลักษณะหลากหลาย [Aspose.Words for Java](https://products.aspose.com/words/java/) เราจะแปลง HTML เป็น ODT
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง PPTX เป็น ODT ผ่าน Java" %}}
1. เปิดไฟล์ PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง PPTX เป็น HTML โดยใช้ [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides ISaveOptions-) และตั้งค่า Html เป็น SaveFormat
3. โหลดไฟล์ HTML ที่แปลงแล้วโดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. บันทึกเอกสารในรูปแบบ ODT โดยใช้วิธีการ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
สำหรับการแปลงไฟล์ PPTX เป็น ODT คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) ตามโครงการและรวมไลบรารีใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
เมื่อใช้ API คุณยังสามารถทำการแปลงไฟล์ PPTX เป็น ODT ด้วยลายน้ำ ในการเพิ่มลายน้ำให้กับเอกสาร ODT ของคุณ ก่อนอื่นให้แปลงไฟล์ PPTX เป็น HTML และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ HTML ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่า คุณสมบัติของมัน วิธี Call Watermark.setText และส่งข้อความลายน้ำ & วัตถุของ TextWatermarkOptions  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-protected-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-word/" name="PPTX ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-dotx/" name="PPTX ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-odt/" name="PPTX ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-ott/" name="PPTX ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-rtf/" name="PPTX ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-flatopc/" name="PPTX ถึง FLAถึงPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-wordml/" name="PPTX ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-odtm/" name="PPTX ถึง ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-text/" name="PPTX ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-odtx/" name="PPTX ถึง ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-dotm/" name="PPTX ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/pptx-to-dot/" name="PPTX ถึง DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}