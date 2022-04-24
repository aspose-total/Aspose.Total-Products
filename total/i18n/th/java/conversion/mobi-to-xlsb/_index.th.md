---
title: Java API เพื่อแปลง MOBI เป็น XLSB
description: แปลง MOBI เป็น XLSB ผ่าน Java โดยไม่ต้องใช้ Microsoft Word หรือ Microsoft Excel
url: /th/java/conversion/mobi-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: MOBI
outformat: XLSB
otherformats: XLSB XLSX TSV XLAM XLT XLSM SXC XLTX XLS FODS ODS XLTM DIF EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง MOBI เป็น XLSB ผ่าน Java" h2="บน Premise Java API เพื่อแปลง MOBI เป็น XLSB โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแปลง MOBI เป็น XLSB ผ่าน [Aspose.Total for Java](https://products.aspose.com/total/java/) เป็นกระบวนการสองขั้นตอนง่ายๆ เมื่อใช้ API การจัดการเอกสารและการแปลงที่มีคุณลักษณะหลากหลาย [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะส่งออก MOBI เป็น HTML ได้ หลังจากนั้น เมื่อใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณจะแปลง HTML เป็น XLSB ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C ++ API เพื่อแปลง MOBI เป็น XLSB" %}}
1. เปิดไฟล์ MOBI โดยใช้คลาส [Mobiument](https://apireference.aspose.com/words/java/com.aspose.words/Mobiument)
2. แปลง MOBI เป็น HTML โดยใช้ [บันทึก](https://apireference.aspose.com/words/java/com.aspose.words/Mobiument#save(java.lang.String,com.aspose.words.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารเป็นรูปแบบ XLSB โดยใช้ [บันทึก](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และรวม [Aspose.Words for Java](https://mobis.aspose.com/words/java/installation/) และ [Aspose.Cells for Java](https://mobis.aspose.com/cells/java/ การติดตั้ง/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ก่อนแปลง MOBI เป็น XLSB คุณสามารถลบข้อมูลที่ไม่ได้ใช้ออกจากเอกสาร MOBI ผ่าน [Aspose.Words for Java](https://products.aspose.com/words/java/) บางครั้ง คุณอาจต้องลบข้อมูลที่ไม่ได้ใช้หรือทำซ้ำเพื่อลดขนาดของเอกสารที่ส่งออกและเวลาในการประมวลผล คลาส [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) ให้คุณระบุตัวเลือกสำหรับการทำความสะอาดเอกสาร หากต้องการลบสไตล์ที่ซ้ำกันหรือเพียงแค่สไตล์หรือรายการที่ไม่ได้ใช้ออกจากเอกสาร คุณสามารถใช้เมธอด [Cleanup](https://apireference.aspose.com/words/java/com.aspose.words/Mobiument#cleanup()) คุณสามารถใช้ [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) และ [UnusedBuiltinStyles](https://apireference.aspose.com/words/java /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) คุณสมบัติเพื่อตรวจจับและลบสไตล์ที่ทำเครื่องหมายเป็น “ไม่ได้ใช้”  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-mobiument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ลบข้อมูลที่ไม่ได้ใช้ออกจากเอกสาร MOBI ผ่าน Java" %}}
หลังจากแปลง MOBI เป็น XLSB แล้ว [Aspose.Cells for Java](https://products.aspose.com/cells/java/) จะช่วยให้คุณบันทึกเอกสารเพื่อสตรีมได้ หากคุณต้องการบันทึกไฟล์ไปยัง Stream คุณควรสร้างวัตถุ FileOutputStream จากนั้น [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) ไฟล์ไปยังวัตถุ Stream นั้นโดยเรียกวิธีการบันทึกของ [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) วัตถุ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-xlsm/" name="MOBI ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-xlt/" name="MOBI ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-ods/" name="MOBI ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-tsv/" name="MOBI ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-xls/" name="MOBI ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-xlsb/" name="MOBI ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-fods/" name="MOBI ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-dif/" name="MOBI ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-xltx/" name="MOBI ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-xlam/" name="MOBI ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-xlsx/" name="MOBI ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-xltm/" name="MOBI ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-sxc/" name="MOBI ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/mobi-to-excel/" name="MOBI ถึง EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}