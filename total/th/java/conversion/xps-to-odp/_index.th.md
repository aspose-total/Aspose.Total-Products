---
title: แปลง XPS เป็น ODP ผ่าน Java API
description: Java API เพื่อแปลง XPS เป็น ODP โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/xps-to-odp/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: ODP
otherformats: POTM PPT PPS POT SWF PPSM PPTM OTP POWERPOINT PPSX POTX XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อส่งออก XPS เป็น ODP" h2="ส่งออก XPS ไปยัง ODP ผ่าน Java API ในองค์กรโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
การใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณสามารถแปลง XPS เป็น ODP ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME ได้อย่างง่ายดาย ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถส่งออก XPS ไปยัง PPTX ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API คุณสามารถแปลง PPTX เป็น ODP ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง XPS เป็น ODP" %}}
1. เปิดไฟล์ XPS โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง XPS เป็น PPTX โดยใช้วิธีการ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ ODP โดยใช้เมธอด [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) และตั้งค่า ` Odp` เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะโหลดรูปแบบไฟล์ XPS เอกสารของคุณอาจมีการป้องกันด้วยรหัสผ่าน [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) ให้คุณเปิดเอกสารที่เข้ารหัสได้เช่นกัน ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดไฟล์ XPS ที่เข้ารหัสผ่าน Java" %}}
หลังจากแปลง XPS เป็น ODP แล้ว คุณยังสามารถเพิ่มประเภทมุมมองที่กำหนดไว้ล่วงหน้าสำหรับงานนำเสนอของคุณได้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) อำนวยความสะดวกในการตั้งค่าประเภทมุมมองสำหรับงานนำเสนอที่สร้างขึ้นเมื่อเปิดใน PowerPoint ผ่าน [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) คลาส [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) ใช้เพื่อตั้งค่าประเภทมุมมองโดยใช้ [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) ตัวแจงนับ 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}