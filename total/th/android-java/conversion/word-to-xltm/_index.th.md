---
title: Android API เพื่อแปลง WORD เป็น XLTM
description: แปลง WORD เป็น XLTM ใน Android ผ่าน Java โดยไม่ต้องใช้ Microsoft Word หรือ Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: XLTM
otherformats: CSV ODS TSV XLAM SXC XLSM XLTX XLSX EXCEL XLSB XLS DIF FODS XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง WORD เป็น XLTM ในแอปพลิเคชัน Android" h2="ส่งออก WORD เป็น XLTM ใน Android ผ่าน Java โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) คุณสามารถรวมคุณลักษณะการแปลง WORD เป็น XLTM ภายในแอปพลิเคชัน Android ของคุณได้ ประการแรก คุณสามารถแปลง WORD เป็น HTML ได้โดยใช้ API การจัดการเอกสารและการแปลงที่มีคุณลักษณะหลากหลาย [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) หลังจากนั้น เมื่อใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/) คุณจะแปลง HTML เป็น XLTM ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อแปลง WORD เป็น XLTM" %}}
1. เปิดไฟล์ WORD โดยใช้คลาส [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument)
2. แปลง WORD เป็น HTML โดยใช้ [Save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,com.aspose.words.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ XLTM โดยใช้ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://releases.aspose.com/total/java/) และ ติดตั้ง [Aspose.Cells for Android via Java](https://words.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) และ [Aspose.Words for Android via Java](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ลบข้อมูลที่ไม่ได้ใช้ออกจากเอกสาร WORD ใน Android ผ่าน Java" %}}
ก่อนแปลง WORD เป็น XLTM คุณสามารถลบข้อมูลที่ไม่ได้ใช้ออกจากเอกสาร WORD ผ่าน [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) บางครั้ง คุณอาจต้องลบข้อมูลที่ไม่ได้ใช้หรือทำซ้ำเพื่อลดขนาดของเอกสารที่ส่งออกและเวลาในการประมวลผล คลาส [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) ให้คุณระบุตัวเลือกสำหรับการทำความสะอาดเอกสาร หากต้องการลบสไตล์ที่ซ้ำกันหรือเพียงแค่สไตล์หรือรายการที่ไม่ได้ใช้ออกจากเอกสาร คุณสามารถใช้เมธอด [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Wordument#cleanup()) คุณสามารถใช้ [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) และ [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) คุณสมบัติในการตรวจหาและลบสไตล์ที่ทำเครื่องหมายเป็น "ไม่ได้ใช้"
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-wordument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="บันทึกไฟล์ XLTM เพื่อสตรีมใน Android ผ่าน Java" %}}
หลังจากแปลง WORD เป็น XLTM แล้ว [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) จะช่วยให้คุณบันทึกเอกสารเพื่อสตรีมได้ หากคุณต้องการบันทึกไฟล์ไปยัง Stream คุณควรสร้างวัตถุ FileOutputStream จากนั้น [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) ไฟล์ไปยังวัตถุ Stream นั้นโดยเรียกวิธีการบันทึกของ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) วัตถุ.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-xltm/" name="WORD ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-ods/" name="WORD ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-tsv/" name="WORD ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-xlam/" name="WORD ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-sxc/" name="WORD ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-xlsm/" name="WORD ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-xltx/" name="WORD ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-xlsx/" name="WORD ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-excel/" name="WORD ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-xlsb/" name="WORD ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-xls/" name="WORD ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-dif/" name="WORD ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-fods/" name="WORD ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/word-to-xlt/" name="WORD ถึง XLT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}