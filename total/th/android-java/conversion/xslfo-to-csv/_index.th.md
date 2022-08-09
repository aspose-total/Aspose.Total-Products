---
title: แปลง XSLFO เป็น CSV ใน Android ผ่าน Java
description: แสดง XSLFO เป็น CSV ใน Android ผ่าน Java API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url: /th/android-java/conversion/xslfo-to-csv/
family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: CSV
otherformats: DIF XLTX XLTM XLSM XLSB XLAM XLT MD TXT FODS EXCEL TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดง XSLFO เป็น CSV ใน Android ผ่าน Java" h2="เปลี่ยน XSLFO เป็น CSV ภายในแอปพลิเคชัน Android โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถรวมคุณลักษณะการแปลง XSLFO เป็น CSV ภายในแอปพลิเคชัน Android ของคุณในกระบวนการสองขั้นตอน ประการแรก โดยใช้ [Aspose.PDF สำหรับ Android ผ่าน Java](https://products.aspose.com/pdf/android-java/) คุณสามารถแปลง XSLFO เป็น XLSX ได้ ประการที่สอง คุณสามารถแปลง XLSX เป็น CSV ได้โดยใช้ API การประมวลผลสเปรดชีตที่มีประสิทธิภาพ [Aspose.Cells สำหรับ Android ผ่าน Java](https://products.aspose.com/cells/android-java/) API ทั้งสองอยู่ภายใต้ [Aspose.Total สำหรับ Android ผ่าน Java](https://products.aspose.com/total/android-java/) ตระกูลผลิตภัณฑ์ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อแสดงผล XSLFO เป็น CSV" %}}
1. เปิดไฟล์ XSLFO โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง XSLFO เป็น XLSX โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) กระบวนการ
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. บันทึกเอกสารในรูปแบบ CSV โดยใช้ [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) วิธีการ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Android ผ่าน Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.PDF สำหรับ Android ผ่าน Java](https://docs.aspose.com/pdf/androidjava/installation/) และ [Aspose.Cells สำหรับ Android ผ่าน Java](https://docs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับข้อมูลเมตา XMP ของไฟล์ XSLFO ใน Android ผ่าน Java" %}}
[Aspose.PDF สำหรับ Android ผ่าน Java](https://products.aspose.com/pdf/android-java/) ให้คุณเข้าถึงข้อมูลเมตา XMP ของไฟล์ XSLFO ในการรับข้อมูลเมตา ให้สร้างออบเจ็กต์ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิดไฟล์ XSLFO อินพุตและใช้ [getMetadata()](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getMetadata--) เพื่อรับข้อมูลเมตา
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "get-pdf-xmp-metadata.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ปกป้องเอกสาร CSV ใน Android ผ่าน Java" %}}
[Aspose.Cells สำหรับ Android ผ่าน Java](https://products.aspose.com/cells/android-java/) รองรับการปกป้องไฟล์ CSV ตามความต้องการของคุณ เพื่อป้องกันเอกสารของคุณ คุณสามารถใช้วิธี [protectSharedWorkbook](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#protectSharedWorkbook(java.lang.String)) ของ [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) คลาส
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "protect-csv.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-dif/" name="XSLFO ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-xltx/" name="XSLFO ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-xltm/" name="XSLFO ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-xlsm/" name="XSLFO ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-xlsb/" name="XSLFO ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-xlam/" name="XSLFO ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-xlt/" name="XSLFO ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-md/" name="XSLFO ถึง MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-txt/" name="XSLFO ถึง TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-fods/" name="XSLFO ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-excel/" name="XSLFO ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-tsv/" name="XSLFO ถึง TSV" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}