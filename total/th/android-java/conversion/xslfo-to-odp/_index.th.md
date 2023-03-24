---
title: ส่งออก XSLFO เป็น ODP ใน Android
description: Android API เพื่อแปลง XSLFO เป็น ODP โดยไม่ต้องใช้ Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: ODP
otherformats: PPT PPSX PPS PPTM PPSM XAML POTM POTX OTP POWERPOINT SWF POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง XSLFO เป็น ODP บน Android ผ่าน Java" h2="เปลี่ยน XSLFO เป็น ODP ภายในแอปพลิเคชัน Android ของคุณโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถรวมคุณลักษณะการแปลง XSLFO เป็น ODP ภายในแอปพลิเคชัน Android ของคุณได้โดยใช้สองขั้นตอนง่ายๆ ในขั้นตอนแรก คุณสามารถส่งออก XSLFO เป็น PPTX ได้โดยใช้ [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) คุณจะสามารถแปลง PPTX เป็น ODP ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อส่งออก XSLFO เป็น ODP" %}}
1. เปิดไฟล์ XSLFO โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง XSLFO เป็น PPTX โดยใช้วิธีการ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ ODP โดยใช้เมธอด [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) และตั้งค่า ` Odp` เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://releases.aspose.com/total/java/) และ ติดตั้ง [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) และ [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="เปิดไฟล์ XSLFO ที่ป้องกันด้วยรหัสผ่านใน Android ผ่าน Java" %}}
ขณะโหลดรูปแบบไฟล์ XSLFO เอกสารของคุณอาจมีการป้องกันด้วยรหัสผ่าน [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ช่วยให้คุณเปิดเอกสารที่เข้ารหัสได้เช่นกัน ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์
{{% blocks/products/pf/feature-page-code %}}

```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างภาพขนาดย่อของไฟล์ ODP ในแอปพลิเคชัน Android" %}}
หลังจากแปลง XSLFO เป็น ODP แล้ว คุณยังสามารถสร้างภาพขนาดย่อของเอกสารผลลัพธ์ของคุณได้ ด้วยการใช้คุณสมบัติมากมาย [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) คุณสามารถสร้างภาพขนาดย่อของสไลด์โดยการสร้างและอินสแตนซ์ของ [การนำเสนอ](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) คลาส หลังจากนั้น คุณสามารถรับข้อมูลอ้างอิงของสไลด์ที่ต้องการได้โดยใช้รหัสหรือดัชนีของสไลด์ และรับภาพขนาดย่อของสไลด์ที่อ้างอิงตามมาตราส่วนที่ระบุ
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("output.odp");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}