---
title: แปลง SVG เป็น PPS ผ่าน Java API
description: Java API เพื่อแปลง SVG เป็น PPS โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/svg-to-pps/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: PPS
otherformats: PPT POT POWERPOINT PPSX PPSM POTM XAML PPS SWF OTP PPTM POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อส่งออก SVG เป็น PPS" h2="ส่งออก SVG ไปยัง PPS ผ่าน Java API ในองค์กรโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
การใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณสามารถแปลง SVG เป็น PPS ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME ได้อย่างง่ายดาย ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถส่งออก SVG ไปยัง PPTX ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API คุณสามารถแปลง PPTX เป็น PPS ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง SVG เป็น PPS" %}}
1. เปิดไฟล์ SVG โดยใช้คลาส [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง SVG เป็น PPTX โดยใช้วิธีการ [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ PPS โดยใช้เมธอด [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) และตั้งค่า ` Pps` เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Slides for Java](https://docs.aspose.com/slides/java/ การติดตั้ง/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะโหลดรูปแบบไฟล์ SVG เอกสารของคุณอาจมีการป้องกันด้วยรหัสผ่าน [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) ให้คุณเปิดเอกสารที่เข้ารหัสได้เช่นกัน ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

```java
// open SVG document
Document doc = new Document("input.svg", "Your@Password");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดไฟล์ SVG ที่เข้ารหัสผ่าน Java" %}}
หลังจากแปลง SVG เป็น PPS แล้ว คุณยังสามารถเพิ่มประเภทมุมมองที่กำหนดไว้ล่วงหน้าสำหรับงานนำเสนอของคุณได้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) อำนวยความสะดวกในการตั้งค่าประเภทมุมมองสำหรับงานนำเสนอที่สร้างขึ้นเมื่อเปิดใน PowerPoint ผ่าน [ViewProperties](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) คลาส [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) ใช้เพื่อตั้งค่าประเภทมุมมองโดยใช้ [ViewType](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewType) ตัวแจงนับ 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-pps/" name="SVG ถึง PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-swf/" name="SVG ถึง SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-potx/" name="SVG ถึง POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-ppsx/" name="SVG ถึง PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-potm/" name="SVG ถึง POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-ppt/" name="SVG ถึง PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-ppsm/" name="SVG ถึง PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-xaml/" name="SVG ถึง XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-otp/" name="SVG ถึง OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-pptm/" name="SVG ถึง PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-pot/" name="SVG ถึง POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/svg-to-powerpoint/" name="SVG ถึง POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}