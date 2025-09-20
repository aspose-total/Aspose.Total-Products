---
title: แปลง EPUB เป็น PPTM ผ่าน Java API
description: Java API เพื่อแปลง EPUB เป็น PPTM โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/epub-to-pptm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPTM
otherformats: PPSX OTP POTM SWF POT PPT XAML POTX PPTM PPS PPSM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อส่งออก EPUB เป็น PPTM" h2="ส่งออก EPUB ไปยัง PPTM ผ่าน Java API ในองค์กรโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
การใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณสามารถแปลง EPUB เป็น PPTM ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME ได้อย่างง่ายดาย ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถส่งออก EPUB ไปยัง PPTX ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API คุณสามารถแปลง PPTX เป็น PPTM ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง EPUB เป็น PPTM" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง EPUB เป็น PPTX โดยใช้วิธีการ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ PPTM โดยใช้เมธอด [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) และตั้งค่า ` Pptm` เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะโหลดรูปแบบไฟล์ EPUB เอกสารของคุณอาจมีการป้องกันด้วยรหัสผ่าน [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) ให้คุณเปิดเอกสารที่เข้ารหัสได้เช่นกัน ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของ [เอกสาร](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) คลาสและส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดไฟล์ EPUB ที่เข้ารหัสผ่าน Java" %}}
หลังจากแปลง EPUB เป็น PPTM แล้ว คุณยังสามารถเพิ่มประเภทมุมมองที่กำหนดไว้ล่วงหน้าสำหรับงานนำเสนอของคุณได้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) อำนวยความสะดวกในการตั้งค่าประเภทมุมมองสำหรับงานนำเสนอที่สร้างขึ้นเมื่อเปิดใน PowerPoint ผ่าน [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) คลาส [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) ใช้เพื่อตั้งค่าประเภทมุมมองโดยใช้ [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) ตัวแจงนับ 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **EPUB เป็น PPTM (งานนำเสนอ PowerPoint ที่เปิดใช้งานแมโคร)** เป็นสิ่งจำเป็นสำหรับสร้าง **งานนำเสนอที่มีปฏิสัมพันธ์พร้อมอัตโนมัติ** จาก eBooks ไฟล์ PPTM รองรับแมโครที่ฝังอยู่ เพื่อให้สามารถสร้างเนื้อหาแบบไดนามิก กระบวนการทำงานอัตโนมัติ และคุณสมบัติที่มีปฏิสัมพันธ์ โดยการแปลง EPUB เป็น PPTM ธุรกิจ ผู้สอน และสำนักพิมพ์สามารถสร้างงานนำเสนออัจฉริยะที่เสริมสร้างความสนใจ มาตรฐานเนื้อหา และปรับปรุงกระบวนการผลิตงานนำเสนอขนาดใหญ่ได้  

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}
- **งานนำเสนอทางธุรกิจและสารสนเทศ** – สร้างสไลด์ที่ไดนามิกพร้อมการอัพเดตข้อมูลและการวิเคราะห์อัตโนมัติ  
- **เนื้อหาการฝึกอบรมอัตโนมัติ** – สร้างงานนำเสนอการฝึกอบรมพร้อมเนื้อหาแบบแมโครและมีปฏิสัมพันธ์  
- **งานนำเสนอการวิจัยทางวิชาการ** – แปลงเนื้อหาทางวิชาการเป็นสไลด์ที่มีโครโมเรื่องโครงสร้างและมีปฏิสัมพันธ์  
- **กระบวนการทำงานสำหรับสำนักพิมพ์** – ปรับปรุงกระบวนการแปลงเนื้อหา eBook เป็นงานนำเสนอที่เปิดใช้งานแมโคร  
- **การอัตโนมัติสไลด์ขององค์กร** – มาตรฐานและอัตโนมัติการสร้างงานนำเสนอขนาดใหญ่ในทีม  
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}
- **กระบวนการทำงาน EPUB เป็น PPTM** – ทำงานแปลง eBook เป็นสไลด์ที่เปิดใช้งานแมโครโดยอัตโนมัติ  
- **การสร้างงานนำเสนอที่เปิดใช้งานแมโครอัตโนมัติ** – ฝังความสามารถในการปฏิสัมพันธ์และคุณสมบัติที่ไดนามิกในสไลด์  
- **การแปลงสไลด์ด้วยข้อมูลเมตาดาต้า** – เติมเนื้อหาในงานนำเสนอโดยใช้ข้อมูล eBook โครงสร้าง  
- **กระบวนการทำงานสำหรับสำนักพิมพ์ขนาดใหญ่** – ขยายการผลิต PPTM ที่เปิดใช้งานแมโครโดยอัตโนมัติในองค์กร  
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}