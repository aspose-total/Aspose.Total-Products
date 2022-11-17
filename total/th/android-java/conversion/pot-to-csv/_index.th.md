---
title: แปลง POT เป็น CSV ใน Android ผ่าน Java
description: แปลง POT เป็น CSV ใน Android ผ่าน Java โดยไม่ต้องใช้ Microsoft Excel หรือ PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: CSV
otherformats: FODS XLTM XLT XLAM MARKDOWN EXCEL MHTML XLSB ODS SXC XLS XLTX XLSX TSV DIF XLSM DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง POT เป็น CSV ใน Android ผ่าน Java" h2="ส่งออกไฟล์ POT เป็น CSV ในแอปพลิเคชัน Android โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลงไฟล์ POT เป็น CSV ในแอปพลิเคชัน Android ของคุณได้อย่างง่ายดายด้วยกระบวนการสองขั้นตอนผ่าน [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ในขั้นตอนแรก คุณสามารถส่งออกไฟล์ POT เป็น HTML ได้โดยใช้ [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) ประการที่สอง โดยใช้ [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) คุณสามารถแปลง HTML เป็น CSV 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง POT เป็น CSV ใน Android" %}}
1. เปิดไฟล์ POT โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง POT เป็น HTML โดยใช้ [Save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesISaveOptions-) วิธีการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ CSV โดยใช้ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ในการแปลง POT เป็น CSV คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และติดตั้งไลบรารีในแอปของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="แปลง Protected POT เป็น CSV ใน Android ผ่าน Java" %}}
คุณยังสามารถเปิดเอกสารที่ป้องกันด้วยรหัสผ่านโดยใช้ API ได้อีกด้วย หากเอกสาร POT ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น CSV ได้โดยไม่ต้องใช้รหัสผ่าน API อนุญาตให้คุณเปิดเอกสารที่เข้ารหัสโดยส่งรหัสผ่านที่ถูกต้องในออบเจกต์ LoadOptions ตัวอย่างโค้ดต่อไปนี้แสดงวิธีลองเปิดเอกสารที่เข้ารหัสด้วยรหัสผ่าน:
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลงไฟล์ POT เป็น CSV พร้อมลายน้ำใน Android" %}}
ขณะแปลงไฟล์ POT เป็น CSV คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ CSV เอาต์พุตของคุณได้ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ HTML ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร HTML ของคุณเป็น CSV ด้วยลายน้ำ
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-fods/" name="POT ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-xltm/" name="POT ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-xlt/" name="POT ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-xlam/" name="POT ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-markdown/" name="POT ถึง MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-excel/" name="POT ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-mhtml/" name="POT ถึง MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-xlsb/" name="POT ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-ods/" name="POT ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-sxc/" name="POT ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-xls/" name="POT ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-xltx/" name="POT ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-xlsx/" name="POT ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-tsv/" name="POT ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-dif/" name="POT ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-xlsm/" name="POT ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-doc/" name="POT ถึง DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-docx/" name="POT ถึง DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-docm/" name="POT ถึง DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-dot/" name="POT ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-dotm/" name="POT ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-dotx/" name="POT ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-odt/" name="POT ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-ott/" name="POT ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-rtf/" name="POT ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-word/" name="POT ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-wordml/" name="POT ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-text/" name="POT ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pot-to-flatopx/" name="POT ถึง FLATOPX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}