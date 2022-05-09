---
title: แปลง ODT เป็น POTM ผ่าน Java
description: Java API เพื่อส่งออก ODT ไปยัง POTM โดยไม่ต้องใช้ Microsoft Word หรือ PowerPoint
url_ignore: /th/java/conversion/odt-to-potm/
family: total
platformtag: net
feature: conversion
informat: ODT
outformat: POTM
otherformats: PPTX POTM POWERPOINT PPT PPTM POTX PPS PPSX POT PPSM CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง ODT เป็น POTM ผ่าน Java" h2="การแปลง ODT เป็น POTM โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
บ่อยครั้งที่นักพัฒนาต้องแปลงไฟล์ ODT เป็น POTM โดยทางโปรแกรม ด้วยการใช้ไลบรารี File Automation Java [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถทำให้กระบวนการแสดงผลเป็นอัตโนมัติในไม่กี่ขั้นตอนง่ายๆ คุณสามารถโหลดไฟล์ ODT ได้โดยใช้ [Aspose.Words for Java](https://products.aspose.com/words/java/) และแปลงเป็น HTML หลังจากนั้นโดยใช้การจัดการ PowerPoint ที่มีประสิทธิภาพ Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) คุณสามารถสร้างงานนำเสนอใหม่ เขียนเนื้อหา HTML ในนั้น และบันทึกเป็น POTM .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง ODT เป็น POTM ผ่าน Java" %}}
1. เปิดไฟล์ ODT โดยใช้คลาส [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. แปลงไฟล์ ODT เป็น HTML โดยใช้ [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) กระบวนการ
3. เริ่มต้นวัตถุ [การนำเสนอ](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) ใหม่
5. แยกเนื้อหาจากไฟล์ HTML โดยใช้ BufferedReader และเขียนเนื้อหาลงในไฟล์นำเสนอของคุณ
6. บันทึกเอกสารไปยัง POTM โดยใช้วิธีการ [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
สำหรับการแปลงไฟล์ ODT เป็น POTM คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) ตามโครงการและรวมไลบรารีใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
API ยังช่วยให้คุณแปลงเอกสาร ODT ที่ป้องกันด้วยรหัสผ่านเป็น POTM หากเอกสาร ODT ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็นรูปแบบ POTM ได้โดยไม่ต้องใช้รหัสผ่าน ในการเปิดเอกสารที่เข้ารหัส คุณสามารถตั้งรหัสผ่านที่ถูกต้องในวัตถุ LoadOptions และส่งผ่านไปยังตัวสร้างเอกสาร  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-odt-to-pptx-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-ppsm/" name="ODT ถึง PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-pot/" name="ODT ถึง POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-powerpoint/" name="ODT ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-pptx/" name="ODT ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-potx/" name="ODT ถึง POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-pptm/" name="ODT ถึง PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-potm/" name="ODT ถึง POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-pps/" name="ODT ถึง PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-ppsx/" name="ODT ถึง PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-ppt/" name="ODT ถึง PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-csv/" name="ODT ถึง CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-dif/" name="ODT ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-fods/" name="ODT ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-ods/" name="ODT ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-sxc/" name="ODT ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-tsv/" name="ODT ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-xlam/" name="ODT ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-xltm/" name="ODT ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-excel/" name="ODT ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-xls/" name="ODT ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-xlsb/" name="ODT ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-xlsm/" name="ODT ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-xlsx/" name="ODT ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-xlt/" name="ODT ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-xltm/" name="ODT ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/odt-to-xltx/" name="ODT ถึง XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}