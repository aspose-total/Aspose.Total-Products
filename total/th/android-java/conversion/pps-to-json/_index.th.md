---
title: แปลง PPS เป็น JSON ใน Android ผ่าน Java
description: แปลง PPS เป็น JSON ใน Android ผ่าน Java โดยไม่ต้องใช้ Microsoft Excel หรือ PowerPoint
url: /th/android-java/conversion/pps-to-json/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง PPS เป็น JSON ใน Android ผ่าน Java" h2="ส่งออกไฟล์ PPS เป็น JSON ในแอปพลิเคชัน Android โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลงไฟล์ PPS เป็น JSON ในแอปพลิเคชัน Android ของคุณได้อย่างง่ายดายด้วยกระบวนการสองขั้นตอนผ่าน [Aspose.Total สำหรับ Android ผ่าน Java](https://products.aspose.com/total/android-java/) ในขั้นตอนแรก คุณสามารถส่งออกไฟล์ PPS เป็น HTML ได้โดยใช้ [Aspose.Slides สำหรับ Android ผ่าน Java](https://products.aspose.com/slides/android-java/) ประการที่สอง โดยใช้ [Aspose.Cells สำหรับ Android ผ่าน Java](https://products.aspose.com/cells/android-java/) คุณสามารถแปลง HTML เป็น JSON 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง PPS เป็น JSON ใน Android" %}}
1. เปิดไฟล์ PPS โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. แปลง PPS เป็น HTML โดยใช้ [บันทึก](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesISaveOptions-) วิธีการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ JSON โดยใช้ [บันทึก](https://reference.aspose.com/cells/java/com.aspose.cells/)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ในการแปลง PPS เป็น JSON คุณสามารถใช้ Aspose.Total สำหรับ Android ผ่าน Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และติดตั้งไลบรารีในแอปของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="แปลง Protected PPS เป็น JSON ใน Android ผ่าน Java" %}}
คุณยังสามารถเปิดเอกสารที่ป้องกันด้วยรหัสผ่านโดยใช้ API ได้อีกด้วย หากเอกสาร PPS ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น JSON ได้โดยไม่ต้องใช้รหัสผ่าน API อนุญาตให้คุณเปิดเอกสารที่เข้ารหัสโดยส่งรหัสผ่านที่ถูกต้องในออบเจกต์ LoadOptions ตัวอย่างโค้ดต่อไปนี้แสดงวิธีลองเปิดเอกสารที่เข้ารหัสด้วยรหัสผ่าน:
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลงไฟล์ PPS เป็น JSON พร้อมลายน้ำใน Android" %}}
ขณะแปลงไฟล์ PPS เป็น JSON คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ JSON เอาต์พุตของคุณได้ ในการเพิ่มลายน้ำ ให้สร้างสมุดงานใหม่เพื่อเปิดไฟล์ HTML ที่แปลงแล้ว เลือกเวิร์กชีตผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน addTextEffect ตั้งค่าสี ความโปร่งใส และอื่นๆ หลังจากนั้น คุณสามารถบันทึกเอกสาร HTML ของคุณเป็น JSON ด้วยลายน้ำ
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-doc/" name="PPS ถึง DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-docm/" name="PPS ถึง DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-docx/" name="PPS ถึง DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-dot/" name="PPS ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-dotm/" name="PPS ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-dotx/" name="PPS ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-odt/" name="PPS ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-ott/" name="PPS ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-rtf/" name="PPS ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-text/" name="PPS ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-word/" name="PPS ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/pps-to-wordml/" name="PPS ถึง WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}