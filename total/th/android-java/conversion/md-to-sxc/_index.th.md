---
title: แปลง MD เป็น SXC ใน Android ผ่าน Java
description: แสดง MD เป็น SXC ใน Android ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: SXC
otherformats: XLTM XLAM EXCEL FODS XLTX DIF XLSM TXT TSV XLSB CSV ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดง MD เป็น SXC ใน Android ผ่าน Java" h2="เปลี่ยน MD เป็น SXC ภายในแอปพลิเคชัน Android โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถรวมคุณลักษณะการแปลง MD เป็น SXC ภายในแอปพลิเคชัน Android ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) คุณสามารถแปลง MD เป็น XLSX ได้ ประการที่สอง คุณสามารถแปลง XLSX เป็น SXC ได้โดยใช้ API การประมวลผลสเปรดชีตที่มีประสิทธิภาพ [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) API ทั้งสองอยู่ภายใต้ [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) ตระกูลผลิตภัณฑ์ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อแสดงผล MD เป็น SXC" %}}
1. เปิดไฟล์ MD โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง MD เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) กระบวนการ
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ SXC โดยใช้ [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) และ [Aspose.Cells for Android via Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับข้อมูลเมตา XMP ของไฟล์ MD ใน Android ผ่าน Java" %}}
[Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ให้คุณเข้าถึงข้อมูลเมตา XMP ของไฟล์ MD ในการรับข้อมูลเมตา ให้สร้างออบเจ็กต์ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิดไฟล์ MD อินพุตและใช้ [getMetadata()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) เพื่อรับข้อมูลเมตา
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ปกป้องเอกสาร SXC ใน Android ผ่าน Java" %}}
[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) รองรับการปกป้องไฟล์ SXC ตามความต้องการของคุณ เพื่อป้องกันเอกสารของคุณ คุณสามารถใช้วิธี [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) ของ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) คลาส
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-sxc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-xltm/" name="MD ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-xlam/" name="MD ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-excel/" name="MD ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-fods/" name="MD ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-xltx/" name="MD ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-dif/" name="MD ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-xlsm/" name="MD ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-txt/" name="MD ถึง TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-tsv/" name="MD ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-xlsb/" name="MD ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-sxc/" name="MD ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/md-to-ods/" name="MD ถึง ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}