---
title: แปลง EPUB เป็น PPS ผ่าน Java API
description: Java API เพื่อแปลง EPUB เป็น PPS โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/epub-to-pps/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPS
otherformats: PPS POTX POTM POT PPSX XAML PPTM PPSM SWF OTP PPT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อส่งออก EPUB เป็น PPS" h2="ส่งออก EPUB ไปยัง PPS ผ่าน Java API ในองค์กรโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
การใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณสามารถแปลง EPUB เป็น PPS ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME ได้อย่างง่ายดาย ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถส่งออก EPUB ไปยัง PPTX ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API คุณสามารถแปลง PPTX เป็น PPS ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง EPUB เป็น PPS" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง EPUB เป็น PPTX โดยใช้วิธีการ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ PPS โดยใช้เมธอด [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) และตั้งค่า ` Pps` เป็น SaveFormat
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
หลังจากแปลง EPUB เป็น PPS แล้ว คุณยังสามารถเพิ่มประเภทมุมมองที่กำหนดไว้ล่วงหน้าสำหรับงานนำเสนอของคุณได้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) อำนวยความสะดวกในการตั้งค่าประเภทมุมมองสำหรับงานนำเสนอที่สร้างขึ้นเมื่อเปิดใน PowerPoint ผ่าน [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) คลาส [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) ใช้เพื่อตั้งค่าประเภทมุมมองโดยใช้ [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) ตัวแจงนับ 
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
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **EPUB เป็น PPS (PowerPoint Show)** เป็นสิ่งจำเป็นสำหรับสร้าง **ไฟล์งานนำเสนอพร้อมเล่น** จากการพิมพ์ดิจิทัล ไฟล์ PPS ช่วยให้สไลด์โชว์เริ่มเล่นทันทีในโหมดนำเสนอ ทำให้เหมาะสำหรับการประชุม การอบรม และการตลาด โดยการแปลง EPUB เป็น PPS ผู้สอน สำนักพิมพ์ และธุรกิจสามารถส่งมอบการนำเสนอที่สวยงามและสะดวกในการเข้าถึงโดยไม่ต้องแก้ไขด้วยมือ เพิ่มประสิทธิภาพในการสื่อสารและการแบ่งปันเนื้อหา

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}
- **สไลด์การประชุม** – สร้างการนำเสนอที่ดูดีสำหรับงานมืออาชีพ
- **การอบรม** – ส่งสไลด์คำสั่งพร้อมเล่นทันที
- **การแสดงตัวอย่างของบ้านพิมพ์** – นำเสนอเนื้อหาหนังสือในรูปแบบสไลด์โชว์แบบอินเทอร์แอคทีฟ
- **การเล่นบทความวิชาการ** – ให้สไลด์บรรยายสำหรับการแสดงผลในห้องเรียนอย่างเรียบร้อย
- **การสาธิตธุรกิจ** – นำเสนอข้อมูลผลิตภัณฑ์หรือบริการในรูปแบบสไลด์โชว์ที่กำหนดไว้ล่วงหน้า
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}
- **ท่อการแปลง EPUB เป็น PPS** – อัตโนมัติการแปลง eBook เป็นสไลด์โชว์พร้อมเล่น
- **การสร้างสไลด์โชว์โดยอัตโนมัติ** – สร้างไฟล์ PPS อย่างรวดเร็วจากการพิมพ์ดิจิทัลหลายรายการ
- **การสร้างโชว์โดยใช้เมตาดาต้า** – เติมเต็มสไลด์โชว์โดยใช้ข้อมูล eBook โครงสร้าง
- **การอัตโนมัติในการพิมพ์ขนาดใหญ่** – รวมการสร้าง PPS เข้ากับขั้นตอนการทำงานใหญ่
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}