---
title: แปลง DOTX เป็น PPSM ผ่าน Java
description: Java API เพื่อส่งออก DOTX ไปยัง PPSM โดยไม่ต้องใช้ Microsoft Word หรือ PowerPoint
url_ignore: /th/java/conversion/dotx-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: PPSM
otherformats: POTX PPSM POT PPTM PPS POTM PPT POWERPOINT PPSX PPTX CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง DOTX เป็น PPSM ผ่าน Java" h2="การแปลง DOTX เป็น PPSM โดยใช้ Java API ภายในภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
บ่อยครั้งที่นักพัฒนาต้องแปลงไฟล์ DOTX เป็น PPSM โดยทางโปรแกรม ด้วยการใช้ไลบรารี File Automation Java [Aspose.Total for Java](https://products.aspose.com/total/java/) คุณสามารถทำให้กระบวนการแสดงผลเป็นอัตโนมัติในไม่กี่ขั้นตอนง่ายๆ คุณสามารถโหลดไฟล์ DOTX ได้โดยใช้ [Aspose.Words for Java](https://products.aspose.com/words/java/) และแปลงเป็น HTML หลังจากนั้นโดยใช้การจัดการ PowerPoint ที่มีประสิทธิภาพ Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/) คุณสามารถสร้างงานนำเสนอใหม่ เขียนเนื้อหา HTML ในนั้น และบันทึกเป็น PPSM .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง DOTX เป็น PPSM ผ่าน Java" %}}
1. เปิดไฟล์ DOTX โดยใช้คลาส [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. แปลงไฟล์ DOTX เป็น HTML โดยใช้ [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) กระบวนการ
3. เริ่มต้นวัตถุ [การนำเสนอ](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) ใหม่
5. แยกเนื้อหาจากไฟล์ HTML โดยใช้ BufferedReader และเขียนเนื้อหาลงในไฟล์นำเสนอของคุณ
6. บันทึกเอกสารไปยัง PPSM โดยใช้วิธีการ [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
สำหรับการแปลงไฟล์ DOTX เป็น PPSM คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจาก [Maven](https://releases.aspose.com/total/java/) ตามโครงการและรวมไลบรารีใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-dotx-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ DOTX เป็น PPSM</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ppsm&from=dotx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
API ยังช่วยให้คุณแปลงเอกสาร DOTX ที่ป้องกันด้วยรหัสผ่านเป็น PPSM หากเอกสาร DOTX ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็นรูปแบบ PPSM ได้โดยไม่ต้องใช้รหัสผ่าน ในการเปิดเอกสารที่เข้ารหัส คุณสามารถตั้งรหัสผ่านที่ถูกต้องในวัตถุ LoadOptions และส่งผ่านไปยังตัวสร้างเอกสาร  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-dotx-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-ppsm/" name="DOTX ถึง PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-pot/" name="DOTX ถึง POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-powerpoint/" name="DOTX ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-pptx/" name="DOTX ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-potx/" name="DOTX ถึง POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-pptm/" name="DOTX ถึง PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-potm/" name="DOTX ถึง POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-pps/" name="DOTX ถึง PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-ppsx/" name="DOTX ถึง PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-ppt/" name="DOTX ถึง PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-csv/" name="DOTX ถึง CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-dif/" name="DOTX ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-fods/" name="DOTX ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-ods/" name="DOTX ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-sxc/" name="DOTX ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-tsv/" name="DOTX ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlam/" name="DOTX ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xltm/" name="DOTX ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-excel/" name="DOTX ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xls/" name="DOTX ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlsb/" name="DOTX ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlsm/" name="DOTX ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlsx/" name="DOTX ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlt/" name="DOTX ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xltm/" name="DOTX ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xltx/" name="DOTX ถึง XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}