---
title: Java API เพื่อแปลง DOCM เป็น EXCEL
description: แปลง DOCM เป็น EXCEL ผ่าน Java โดยไม่ต้องใช้ Microsoft Word หรือ Microsoft Excel
url_ignore: /th/java/conversion/docm-to-excel/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: XLSX
otherformats: XLTM EXCEL XLAM ODS EXCEL XLT XLSX FODS XLTX SXC XLSB TSV XLSM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง DOCM เป็น EXCEL ผ่าน Java" h2="บน Premise Java API เพื่อแปลง DOCM เป็น EXCEL โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
การแปลง DOCM เป็น EXCEL ผ่าน [Aspose.Total for Java](https://products.aspose.com/total/java/) เป็นกระบวนการสองขั้นตอนง่ายๆ เมื่อใช้ API การจัดการเอกสารและการแปลงที่มีคุณลักษณะหลากหลาย [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะส่งออก DOCM เป็น HTML ได้ หลังจากนั้น เมื่อใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/java/) คุณจะแปลง HTML เป็น EXCEL ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C ++ API เพื่อแปลง DOCM เป็น EXCEL" %}}
1. เปิดไฟล์ DOCM โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. แปลง DOCM เป็น HTML โดยใช้ [บันทึก](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารเป็นรูปแบบ EXCEL โดยใช้ [บันทึก](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และรวม [Aspose.Words for Java](https://docms.aspose.com/words/java/installation/) และ [Aspose.Cells for Java](https://docms.aspose.com/cells/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}Document
ก่อนแปลง DOCM เป็น EXCEL คุณสามารถลบข้อมูลที่ไม่ได้ใช้ออกจากเอกสาร DOCM ผ่าน [Aspose.Words for Java](https://products.aspose.com/words/java/) บางครั้ง คุณอาจต้องลบข้อมูลที่ไม่ได้ใช้หรือทำซ้ำเพื่อลดขนาดของเอกสารที่ส่งออกและเวลาในการประมวลผล คลาส [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) ให้คุณระบุตัวเลือกสำหรับการทำความสะอาดเอกสาร หากต้องการลบสไตล์ที่ซ้ำกันหรือเพียงแค่สไตล์หรือรายการที่ไม่ได้ใช้ออกจากเอกสาร คุณสามารถใช้เมธอด [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Document#cleanup()) คุณสามารถใช้ [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) และ [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) คุณสมบัติเพื่อตรวจจับและลบสไตล์ที่ทำเครื่องหมายเป็น “ไม่ได้ใช้”  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="ลบข้อมูลที่ไม่ได้ใช้ออกจากเอกสาร DOCM ผ่าน Java" %}}
หลังจากแปลง DOCM เป็น EXCEL แล้ว [Aspose.Cells for Java](https://products.aspose.com/cells/java/) จะช่วยให้คุณบันทึกเอกสารเพื่อสตรีมได้ หากคุณต้องการบันทึกไฟล์ไปยัง Stream คุณควรสร้างวัตถุ FileOutputStream จากนั้น [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) ไฟล์ไปยังวัตถุ Stream นั้นโดยเรียกวิธีการบันทึกของ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) วัตถุ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-xlsm/" name="DOCM ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-xlt/" name="DOCM ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-ods/" name="DOCM ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-tsv/" name="DOCM ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-xls/" name="DOCM ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-xlsb/" name="DOCM ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-fods/" name="DOCM ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-dif/" name="DOCM ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-xltx/" name="DOCM ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-xlam/" name="DOCM ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-xlsx/" name="DOCM ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-xltm/" name="DOCM ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-sxc/" name="DOCM ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docm-to-excel/" name="DOCM ถึง EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}