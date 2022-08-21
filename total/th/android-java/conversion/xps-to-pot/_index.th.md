---
title: ส่งออก XPS เป็น POT ใน Android
description: Android API เพื่อแปลง XPS เป็น POT โดยไม่ต้องใช้ Microsoft Word
url: /th/android-java/conversion/xps-to-pot/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: POT
otherformats: PPSM OTP PPS PPTM PPT POTM POWERPOINT XAML ODP POTX SWF PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง XPS เป็น POT บน Android ผ่าน Java" h2="เปลี่ยน XPS เป็น POT ภายในแอปพลิเคชัน Android ของคุณโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถรวมคุณลักษณะการแปลง XPS เป็น POT ภายในแอปพลิเคชัน Android ของคุณได้โดยใช้สองขั้นตอนง่ายๆ ในขั้นตอนแรก คุณสามารถส่งออก XPS เป็น PPTX ได้โดยใช้ [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) คุณจะสามารถแปลง PPTX เป็น POT ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อส่งออก XPS เป็น POT" %}}
1. เปิดไฟล์ XPS โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง XPS เป็น PPTX โดยใช้วิธีการ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ POT โดยใช้เมธอด [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) และตั้งค่า ` Pot` เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) และ [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="เปิดไฟล์ XPS ที่ป้องกันด้วยรหัสผ่านใน Android ผ่าน Java" %}}
ขณะโหลดรูปแบบไฟล์ XPS เอกสารของคุณอาจมีการป้องกันด้วยรหัสผ่าน [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ช่วยให้คุณเปิดเอกสารที่เข้ารหัสได้เช่นกัน ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="สร้างภาพขนาดย่อของไฟล์ POT ในแอปพลิเคชัน Android" %}}
หลังจากแปลง XPS เป็น POT แล้ว คุณยังสามารถสร้างภาพขนาดย่อของเอกสารผลลัพธ์ของคุณได้ ด้วยการใช้คุณสมบัติมากมาย [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) คุณสามารถสร้างภาพขนาดย่อของสไลด์โดยการสร้างและอินสแตนซ์ของ [การนำเสนอ]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) คลาส หลังจากนั้น คุณสามารถรับข้อมูลอ้างอิงของสไลด์ที่ต้องการได้โดยใช้รหัสหรือดัชนีของสไลด์ และรับภาพขนาดย่อของสไลด์ที่อ้างอิงตามมาตราส่วนที่ระบุ
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("output.pot");
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
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-ppsm/" name="XPS ถึง PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-otp/" name="XPS ถึง OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-pps/" name="XPS ถึง PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-pptm/" name="XPS ถึง PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-ppt/" name="XPS ถึง PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-potm/" name="XPS ถึง POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-powerpoint/" name="XPS ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-xaml/" name="XPS ถึง XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-pot/" name="XPS ถึง POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-potx/" name="XPS ถึง POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-swf/" name="XPS ถึง SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xps-to-ppsx/" name="XPS ถึง PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}