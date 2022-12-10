---
title: Android API เพื่อแปลง OTT เป็น XLT
description: แปลง OTT เป็น XLT ใน Android ผ่าน Java โดยไม่ต้องใช้ Microsoft Word หรือ Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: OTT
outformat: XLT
otherformats: DIF XLSB ODS XLSM XLAM EXCEL XLS CSV XLSX TSV XLTX FODS XLTM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง OTT เป็น XLT ในแอปพลิเคชัน Android" h2="ส่งออก OTT เป็น XLT ใน Android ผ่าน Java โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) คุณสามารถรวมคุณลักษณะการแปลง OTT เป็น XLT ภายในแอปพลิเคชัน Android ของคุณได้ ประการแรก คุณสามารถแปลง OTT เป็น HTML ได้โดยใช้ API การจัดการเอกสารและการแปลงที่มีคุณลักษณะหลากหลาย [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) หลังจากนั้น เมื่อใช้ [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/) คุณจะแปลง HTML เป็น XLT ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อแปลง OTT เป็น XLT" %}}
1. เปิดไฟล์ OTT โดยใช้คลาส [Ottument](https://reference.aspose.com/words/java/com.aspose.words/Ottument)
2. แปลง OTT เป็น HTML โดยใช้ [Save](https://reference.aspose.com/words/java/com.aspose.words/Ottument#save(java.lang.String,com.aspose.words.SaveOptions) ) กระบวนการ
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ XLT โดยใช้ [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://releases.aspose.com/total/java/) และ ติดตั้ง [Aspose.Cells for Android via Java](https://otts.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) และ [Aspose.Words for Android via Java](https://otts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ลบข้อมูลที่ไม่ได้ใช้ออกจากเอกสาร OTT ใน Android ผ่าน Java" %}}
ก่อนแปลง OTT เป็น XLT คุณสามารถลบข้อมูลที่ไม่ได้ใช้ออกจากเอกสาร OTT ผ่าน [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) บางครั้ง คุณอาจต้องลบข้อมูลที่ไม่ได้ใช้หรือทำซ้ำเพื่อลดขนาดของเอกสารที่ส่งออกและเวลาในการประมวลผล คลาส [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) ให้คุณระบุตัวเลือกสำหรับการทำความสะอาดเอกสาร หากต้องการลบสไตล์ที่ซ้ำกันหรือเพียงแค่สไตล์หรือรายการที่ไม่ได้ใช้ออกจากเอกสาร คุณสามารถใช้เมธอด [Cleanup](https://reference.aspose.com/words/java/com.aspose.words/Ottument#cleanup()) คุณสามารถใช้ [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) และ [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedBuiltinStyles) คุณสมบัติในการตรวจหาและลบสไตล์ที่ทำเครื่องหมายเป็น "ไม่ได้ใช้"
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-ottument.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="บันทึกไฟล์ XLT เพื่อสตรีมใน Android ผ่าน Java" %}}
หลังจากแปลง OTT เป็น XLT แล้ว [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) จะช่วยให้คุณบันทึกเอกสารเพื่อสตรีมได้ หากคุณต้องการบันทึกไฟล์ไปยัง Stream คุณควรสร้างวัตถุ FileOutputStream จากนั้น [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) ไฟล์ไปยังวัตถุ Stream นั้นโดยเรียกวิธีการบันทึกของ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) วัตถุ.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-dif/" name="OTT ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-xlsb/" name="OTT ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-ods/" name="OTT ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-xlsm/" name="OTT ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-xlam/" name="OTT ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-excel/" name="OTT ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-xls/" name="OTT ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-xlt/" name="OTT ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-xlsx/" name="OTT ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-tsv/" name="OTT ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-xltx/" name="OTT ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-fods/" name="OTT ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-xltm/" name="OTT ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/ott-to-sxc/" name="OTT ถึง SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}