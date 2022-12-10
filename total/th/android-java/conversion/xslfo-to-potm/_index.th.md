---
title: ส่งออก XSLFO เป็น POTM ใน Android
description: Android API เพื่อแปลง XSLFO เป็น POTM โดยไม่ต้องใช้ Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: POTM
otherformats: PPT ODP XAML OTP PPTM PPS POWERPOINT PPSX PPSM POTX SWF POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง XSLFO เป็น POTM บน Android ผ่าน Java" h2="เปลี่ยน XSLFO เป็น POTM ภายในแอปพลิเคชัน Android ของคุณโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถรวมคุณลักษณะการแปลง XSLFO เป็น POTM ภายในแอปพลิเคชัน Android ของคุณได้โดยใช้สองขั้นตอนง่ายๆ ในขั้นตอนแรก คุณสามารถส่งออก XSLFO เป็น PPTX ได้โดยใช้ [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) คุณจะสามารถแปลง PPTX เป็น POTM ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อส่งออก XSLFO เป็น POTM" %}}
1. เปิดไฟล์ XSLFO โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง XSLFO เป็น PPTX โดยใช้วิธีการ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ POTM โดยใช้เมธอด [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) และตั้งค่า ` Potm` เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และ ติดตั้ง [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) และ [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) ในแอปพลิเคชันของคุณ

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
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);   
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

{{% blocks/products/pf/feature-page-section  h2="สร้างภาพขนาดย่อของไฟล์ POTM ในแอปพลิเคชัน Android" %}}
หลังจากแปลง XSLFO เป็น POTM แล้ว คุณยังสามารถสร้างภาพขนาดย่อของเอกสารผลลัพธ์ของคุณได้ ด้วยการใช้คุณสมบัติมากมาย [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) คุณสามารถสร้างภาพขนาดย่อของสไลด์โดยการสร้างและอินสแตนซ์ของ [การนำเสนอ](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) คลาส หลังจากนั้น คุณสามารถรับข้อมูลอ้างอิงของสไลด์ที่ต้องการได้โดยใช้รหัสหรือดัชนีของสไลด์ และรับภาพขนาดย่อของสไลด์ที่อ้างอิงตามมาตราส่วนที่ระบุ
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("output.potm");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-ppt/" name="XSLFO ถึง PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-potm/" name="XSLFO ถึง POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-xaml/" name="XSLFO ถึง XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-otp/" name="XSLFO ถึง OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-pptm/" name="XSLFO ถึง PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-pps/" name="XSLFO ถึง PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-powerpoint/" name="XSLFO ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-ppsx/" name="XSLFO ถึง PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-ppsm/" name="XSLFO ถึง PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-potx/" name="XSLFO ถึง POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-swf/" name="XSLFO ถึง SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/android-java/conversion/xslfo-to-pot/" name="XSLFO ถึง POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}