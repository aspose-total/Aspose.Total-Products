---
title: แปลง POTX เป็น XLSB ใน Android ผ่าน Java
description: แปลง POTX เป็น XLSB ใน Android ผ่าน Java โดยไม่ต้องใช้ Microsoft Excel หรือ PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: XLSB
otherformats: XLAM XLT XLS XLSX SXC EXCEL DIF TSV XLTM CSV MHTML FODS MARKDOWN XLTX ODS XLSM DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง POTX เป็น XLSB ใน Android ผ่าน Java" h2="ส่งออกไฟล์ POTX เป็น XLSB ในแอปพลิเคชัน Android โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลงไฟล์ POTX เป็น XLSB ในแอปพลิเคชัน Android ของคุณได้อย่างง่ายดายด้วยกระบวนการสองขั้นตอนผ่าน [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ในขั้นตอนแรก คุณสามารถส่งออกไฟล์ POTX เป็น HTML ได้โดยใช้ [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) ประการที่สอง โดยใช้ [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) คุณสามารถแปลง HTML เป็น XLSB 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง POTX เป็น XLSB ใน Android" %}}
1. เปิดไฟล์ POTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง POTX เป็น HTML โดยใช้ [Save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesISaveOptions-) วิธีการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ XLSB โดยใช้ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ในการแปลง POTX เป็น XLSB คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และติดตั้งไลบรารีในแอปของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="แปลง Protected POTX เป็น XLSB ใน Android ผ่าน Java" %}}
คุณยังสามารถเปิดเอกสารที่ป้องกันด้วยรหัสผ่านโดยใช้ API ได้อีกด้วย หากเอกสาร POTX ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น XLSB ได้โดยไม่ต้องใช้รหัสผ่าน API อนุญาตให้คุณเปิดเอกสารที่เข้ารหัสโดยส่งรหัสผ่านที่ถูกต้องในออบเจกต์ LoadOptions ตัวอย่างโค้ดต่อไปนี้แสดงวิธีลองเปิดเอกสารที่เข้ารหัสด้วยรหัสผ่าน:
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลงไฟล์ POTX เป็น XLSB พร้อมลายน้ำใน Android" %}}
ขณะแปลงไฟล์ POTX เป็น XLSB คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ XLSB เอาต์พุตของคุณได้ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ HTML ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร HTML ของคุณเป็น XLSB ด้วยลายน้ำ
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-xlam/" name="POTX ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-xlt/" name="POTX ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-xls/" name="POTX ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-xlsx/" name="POTX ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-sxc/" name="POTX ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-excel/" name="POTX ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-dif/" name="POTX ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-tsv/" name="POTX ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-xltm/" name="POTX ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-xlsb/" name="POTX ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-mhtml/" name="POTX ถึง MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-fods/" name="POTX ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-markdown/" name="POTX ถึง MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-xltx/" name="POTX ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-ods/" name="POTX ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-xlsm/" name="POTX ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-doc/" name="POTX ถึง DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-docx/" name="POTX ถึง DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-docm/" name="POTX ถึง DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-dot/" name="POTX ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-dotm/" name="POTX ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-dotx/" name="POTX ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-odt/" name="POTX ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-ott/" name="POTX ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-rtf/" name="POTX ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-word/" name="POTX ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-wordml/" name="POTX ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-text/" name="POTX ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/potx-to-flatopx/" name="POTX ถึง FLATOPX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}