---
title: แปลง TEX เป็น TSV ใน Android ผ่าน Java
description: แสดง TEX เป็น TSV ใน Android ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url: /th/android-java/conversion/tex-to-tsv/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: TSV
otherformats: CSV XLTX EXCEL SXC FODS DIF XLT XLSM XLSB MD ODS XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดง TEX เป็น TSV ใน Android ผ่าน Java" h2="เปลี่ยน TEX เป็น TSV ภายในแอปพลิเคชัน Android โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถรวมคุณลักษณะการแปลง TEX เป็น TSV ภายในแอปพลิเคชัน Android ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF สำหรับ Android ผ่าน Java](https://products.aspose.com/pdf/android-java/) คุณสามารถแปลง TEX เป็น XLSX ได้ ประการที่สอง คุณสามารถแปลง XLSX เป็น TSV ได้โดยใช้ API การประมวลผลสเปรดชีตที่มีประสิทธิภาพ [Aspose.Cells สำหรับ Android ผ่าน Java](https://products.aspose.com/cells/android-java/) API ทั้งสองอยู่ภายใต้ [Aspose.Total สำหรับ Android ผ่าน Java](https://products.aspose.com/total/android-java/) ตระกูลผลิตภัณฑ์ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อแสดงผล TEX เป็น TSV" %}}
1. เปิดไฟล์ TEX โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง TEX เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) กระบวนการ
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ TSV โดยใช้ [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Android ผ่าน Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.PDF สำหรับ Android ผ่าน Java](https://docs.aspose.com/pdf/androidjava/installation/) และ [Aspose.Cells สำหรับ Android ผ่าน Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับข้อมูลเมตา XMP ของไฟล์ TEX ใน Android ผ่าน Java" %}}
[Aspose.PDF สำหรับ Android ผ่าน Java](https://products.aspose.com/pdf/android-java/) ให้คุณเข้าถึงข้อมูลเมตา XMP ของไฟล์ TEX ในการรับข้อมูลเมตา ให้สร้างออบเจ็กต์ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิดไฟล์ TEX อินพุตและใช้ [getMetadata()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) เพื่อรับข้อมูลเมตา
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ปกป้องเอกสาร TSV ใน Android ผ่าน Java" %}}
[Aspose.Cells สำหรับ Android ผ่าน Java](https://products.aspose.com/cells/android-java/) รองรับการปกป้องไฟล์ TSV ตามความต้องการของคุณ เพื่อป้องกันเอกสารของคุณ คุณสามารถใช้วิธี [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) ของ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) คลาส
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-tsv.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-tsv/" name="TEX ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-xltx/" name="TEX ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-excel/" name="TEX ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-sxc/" name="TEX ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-fods/" name="TEX ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-dif/" name="TEX ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-xlt/" name="TEX ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-xlsm/" name="TEX ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-xlsb/" name="TEX ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-md/" name="TEX ถึง MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-ods/" name="TEX ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/tex-to-xltm/" name="TEX ถึง XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}