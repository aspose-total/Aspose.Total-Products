---
title: แปลง DOCX เป็น POTM ผ่าน Java หรือทางออนไลน์
description: Java API เพื่อส่งออก DOCX ไปยัง POTM โดยไม่ต้องใช้ Microsoft Word หรือ PowerPoint หรือทางออนไลน์ ทดสอบตัวแปลง POT เป็น CSV ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด หรือด้วยตัวแปลงออนไลน์ฟรี
url_ignore: /th/java/conversion/docx-to-potm/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: POTM
otherformats: PPT PPTX POT PPSX PPSM POWERPOINT PPTM PPS POTM POTX CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง DOCX เป็น POTM ผ่าน Java หรือทางออนไลน์" h2="การแปลง DOCX เป็น POTM โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
บ่อยครั้งที่นักพัฒนาต้องแปลงไฟล์ DOCX เป็น POTM โดยทางโปรแกรม ด้วยการใช้ไลบรารี File Automation Java [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถทำให้กระบวนการแสดงผลเป็นอัตโนมัติในไม่กี่ขั้นตอนง่ายๆ คุณสามารถโหลดไฟล์ DOCX ได้โดยใช้ [Aspose.Words for Java](https://products.aspose.com/words/java/) และแปลงเป็น HTML หลังจากนั้นโดยใช้การจัดการ PowerPoint ที่มีประสิทธิภาพ Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) คุณสามารถสร้างงานนำเสนอใหม่ เขียนเนื้อหา HTML ในนั้น และบันทึกเป็น POTM .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง DOCX เป็น POTM ผ่าน Java หรือทางออนไลน์" %}}
1. เปิดไฟล์ DOCX โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. แปลงไฟล์ DOCX เป็น HTML โดยใช้ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) กระบวนการ
3. เริ่มต้นวัตถุ [การนำเสนอ](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) ใหม่
5. แยกเนื้อหาจากไฟล์ HTML โดยใช้ BufferedReader และเขียนเนื้อหาลงในไฟล์นำเสนอของคุณ
6. บันทึกเอกสารไปยัง POTM โดยใช้วิธีการ [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
สำหรับการแปลงไฟล์ DOCX เป็น POTM คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจาก [Maven](https://releases.aspose.com/total/java/) ตามโครงการและรวมไลบรารีใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-docx-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ DOCX เป็น POTM</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=potm&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
API ยังช่วยให้คุณแปลงเอกสาร DOCX ที่ป้องกันด้วยรหัสผ่านเป็น POTM หากเอกสาร DOCX ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็นรูปแบบ POTM ได้โดยไม่ต้องใช้รหัสผ่าน ในการเปิดเอกสารที่เข้ารหัส คุณสามารถตั้งรหัสผ่านที่ถูกต้องในวัตถุ LoadOptions และส่งผ่านไปยังตัวสร้างเอกสาร  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-docx-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-ppsm/" name="DOCX ถึง PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-pot/" name="DOCX ถึง POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-powerpoint/" name="DOCX ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-pptx/" name="DOCX ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-potx/" name="DOCX ถึง POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-pptm/" name="DOCX ถึง PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-potm/" name="DOCX ถึง POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-pps/" name="DOCX ถึง PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-ppsx/" name="DOCX ถึง PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-ppt/" name="DOCX ถึง PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-csv/" name="DOCX ถึง CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-dif/" name="DOCX ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-fods/" name="DOCX ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-ods/" name="DOCX ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-sxc/" name="DOCX ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-tsv/" name="DOCX ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-xlam/" name="DOCX ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-xltm/" name="DOCX ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-excel/" name="DOCX ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-xls/" name="DOCX ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-xlsb/" name="DOCX ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-xlsm/" name="DOCX ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-xlsx/" name="DOCX ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-xlt/" name="DOCX ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-xltm/" name="DOCX ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/docx-to-xltx/" name="DOCX ถึง XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}