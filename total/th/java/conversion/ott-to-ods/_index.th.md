---
title: Java API เพื่อแปลง OTT เป็น ODS
description: แปลง OTT เป็น ODS ผ่าน Java โดยไม่ต้องใช้ Microsoft Word หรือ Microsoft Excel
url_ignore: /th/java/conversion/ott-to-ods/
family: total
platformtag: net
feature: conversion
informat: OTT
outformat: ODS
otherformats: XLTX XLT XLS SXC XLTM XLSX XLSB XLAM TSV EXCEL XLSM ODS DIF FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง OTT เป็น ODS ผ่าน Java" h2="บน Premise Java API เพื่อแปลง OTT เป็น ODS โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแปลง OTT เป็น ODS ผ่าน [Aspose.Total for Java](https://products.aspose.com/total/java/) เป็นกระบวนการสองขั้นตอนง่ายๆ เมื่อใช้ API การจัดการเอกสารและการแปลงที่มีคุณลักษณะหลากหลาย [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะส่งออก OTT เป็น HTML ได้ หลังจากนั้น เมื่อใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณจะแปลง HTML เป็น ODS ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C ++ API เพื่อแปลง OTT เป็น ODS" %}}
1. เปิดไฟล์ OTT โดยใช้คลาส [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. แปลง OTT เป็น HTML โดยใช้ [บันทึก](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารเป็นรูปแบบ ODS โดยใช้ [บันทึก](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และรวม [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) และ [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}/Document
ก่อนแปลง OTT เป็น ODS คุณสามารถลบข้อมูลที่ไม่ได้ใช้ออกจากเอกสาร OTT ผ่าน [Aspose.Words for Java](https://products.aspose.com/words/java/) บางครั้ง คุณอาจต้องลบข้อมูลที่ไม่ได้ใช้หรือทำซ้ำเพื่อลดขนาดของเอกสารที่ส่งออกและเวลาในการประมวลผล คลาส [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) ให้คุณระบุตัวเลือกสำหรับการทำความสะอาดเอกสาร หากต้องการลบสไตล์ที่ซ้ำกันหรือเพียงแค่สไตล์หรือรายการที่ไม่ได้ใช้ออกจากเอกสาร คุณสามารถใช้เมธอด [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Document#cleanup()) คุณสามารถใช้ [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) และ [UnusedBuiltinStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) คุณสมบัติเพื่อตรวจจับและลบสไตล์ที่ทำเครื่องหมายเป็น “ไม่ได้ใช้”  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ลบข้อมูลที่ไม่ได้ใช้ออกจากเอกสาร OTT ผ่าน Java" %}}
หลังจากแปลง OTT เป็น ODS แล้ว [Aspose.Cells for Java](https://products.aspose.com/cells/java/) จะช่วยให้คุณบันทึกเอกสารเพื่อสตรีมได้ หากคุณต้องการบันทึกไฟล์ไปยัง Stream คุณควรสร้างวัตถุ FileOutputStream จากนั้น [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) ไฟล์ไปยังวัตถุ Stream นั้นโดยเรียกวิธีการบันทึกของ [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) วัตถุ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-xlsm/" name="OTT ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-xlt/" name="OTT ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-ods/" name="OTT ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-tsv/" name="OTT ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-xls/" name="OTT ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-xlsb/" name="OTT ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-fods/" name="OTT ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-dif/" name="OTT ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-xltx/" name="OTT ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-xlam/" name="OTT ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-xlsx/" name="OTT ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-xltm/" name="OTT ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-sxc/" name="OTT ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ott-to-excel/" name="OTT ถึง EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}