---
title: แปลง PS เป็น PPSM ผ่าน Java API
description: Java API เพื่อแปลง PS เป็น PPSM โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/ps-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPSM
otherformats: PPS PPSX XAML POWERPOINT POT PPSM POTX PPTM OTP POTM SWF PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อส่งออก PS เป็น PPSM" h2="ส่งออก PS ไปยัง PPSM ผ่าน Java API ในองค์กรโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
การใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณสามารถแปลง PS เป็น PPSM ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME ได้อย่างง่ายดาย ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถส่งออก PS ไปยัง PPTX ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API คุณสามารถแปลง PPTX เป็น PPSM ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง PS เป็น PPSM" %}}
1. เปิดไฟล์ PS โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง PS เป็น PPTX โดยใช้วิธีการ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ PPSM โดยใช้เมธอด [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) และตั้งค่า ` Ppsm` เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะโหลดรูปแบบไฟล์ PS เอกสารของคุณอาจมีการป้องกันด้วยรหัสผ่าน [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) ให้คุณเปิดเอกสารที่เข้ารหัสได้เช่นกัน ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดไฟล์ PS ที่เข้ารหัสผ่าน Java" %}}
หลังจากแปลง PS เป็น PPSM แล้ว คุณยังสามารถเพิ่มประเภทมุมมองที่กำหนดไว้ล่วงหน้าสำหรับงานนำเสนอของคุณได้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) อำนวยความสะดวกในการตั้งค่าประเภทมุมมองสำหรับงานนำเสนอที่สร้างขึ้นเมื่อเปิดใน PowerPoint ผ่าน [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) คลาส [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) ใช้เพื่อตั้งค่าประเภทมุมมองโดยใช้ [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) ตัวแจงนับ 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

การแปลงไฟล์ PS (PostScript) เป็น PPSM (PowerPoint Macro-Enabled Show) ช่วยให้สามารถสร้างงานนำเสนอที่เชื่อมโยงและอัตโนมัติได้  PPSM จะรักษาแมโครที่ฝังอยู่ในสไลด์เพื่อให้มีพฤติกรรมที่เปลี่ยนไปได้ เช่น การอัปเดตข้อมูลหรือแผนภูมิที่สามารถทำงานได้

{{% blocks/products/pf/agp/feature-section-col title="Key Use Cases" %}}

* สร้างงานนำเสนอที่เชื่อมโยงและมีแมโครจากไดอะแกรม PS
* อัตโนมัติการอัปเดตสไลด์ตามข้อมูลในงานนำเสนอของลูกค้าหรือการฝึกอบรม
* ฝังแผนภูมิและไดอะแกรม PostScript ลงในการนำเสนอสไลด์ที่เปลี่ยนไปได้
* มาตรฐานเทมเพลตงานนำเสนอที่เชื่อมโยงสำหรับการใช้งานในองค์กร

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Automation Scenarios" %}}

* การแปลงจำนวนมากของไฟล์ PS เป็น PPSM สำหรับการทำงานอัตโนมัติในองค์กร
* การผสานกับแพลตฟอร์มการวิเคราะห์และรายงานสำหรับการอัปเดตสไลด์ที่เปลี่ยนไปได้
* การแปลงรายงาน PS เป็นงานนำเสนอที่เปิดใช้แมโครตามกำหนดเวลา
* การฝังแมโครด้วยการช่วยเหลือของ AI เพื่อพฤติกรรมสไลด์ที่เชื่อมโยง

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}