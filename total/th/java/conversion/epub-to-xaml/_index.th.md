---
title: แปลง EPUB เป็น XAML ผ่าน Java API
description: Java API เพื่อแปลง EPUB เป็น XAML โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/java/conversion/epub-to-xaml/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: XAML
otherformats: PPS PPSM OTP SWF PPSX POT POTX POWERPOINT XAML PPT PPTM POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API เพื่อส่งออก EPUB เป็น XAML" h2="ส่งออก EPUB ไปยัง XAML ผ่าน Java API ในองค์กรโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
การใช้ [Aspose.Total สำหรับ Java](https://products.aspose.com/total/java/) คุณสามารถแปลง EPUB เป็น XAML ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME ได้อย่างง่ายดาย ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถส่งออก EPUB ไปยัง PPTX ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API คุณสามารถแปลง PPTX เป็น XAML ได้
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง EPUB เป็น XAML" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง EPUB เป็น PPTX โดยใช้วิธีการ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ XAML โดยใช้เมธอด [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) และตั้งค่า ` Xaml` เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-xaml.java" >}}
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
หลังจากแปลง EPUB เป็น XAML แล้ว คุณยังสามารถเพิ่มประเภทมุมมองที่กำหนดไว้ล่วงหน้าสำหรับงานนำเสนอของคุณได้ [Aspose.Slides for Java](https://products.aspose.com/slides/java/) อำนวยความสะดวกในการตั้งค่าประเภทมุมมองสำหรับงานนำเสนอที่สร้างขึ้นเมื่อเปิดใน PowerPoint ผ่าน [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) คลาส [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) ใช้เพื่อตั้งค่าประเภทมุมมองโดยใช้ [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) ตัวแจงนับ 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Xaml format
presentation.save("output.xaml", SaveFormat.Xaml);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **EPUB เป็น XAML** เป็นสิ่งจำเป็นสำหรับการสร้าง **UI-friendly markup** จากเนื้อหาของ eBook ไฟล์ XAML ช่วยให้นักออกแบบและนักพัฒนาสามารถสร้างอินเทอร์เฟซที่สามารถโต้ตอบ ปรับขนาด และเข้ากันได้กับ Windows ได้โดยตรงจากเนื้อหาของการตีพิมพ์ โดยการแปลง EPUB เป็น XAML ทีมสามารถปรับปรุงการจำลองแอปพลิเคชัน ปรับปรุงการทำงานของ UI/UX และผสานทรัพยากรการตีพิมพ์เข้าสู่โครงการ Windows Presentation Foundation (WPF)  

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}
- **การจำลองแอปพลิเคชัน** – แปลงเนื้อหาอย่างรวดเร็วเป็นมาร์กอัพพร้อมใช้งานสำหรับแอปพลิเคชัน  
- **การทำงานของ UI/UX** – ผสานองค์ประกอบของ eBook เข้าสู่ระบบการออกแบบแบบแอคทีฟ  
- **การเผยแพร่แบบ跨แพลตฟอร์ม** – ปรับเนื้อหาสำหรับโครงการ UI ที่ใช้งานได้หลายอุปกรณ์และหลายแพลตฟอร์ม  
- **การออกแบบแบบแอคทีฟ** – สร้างอินเทอร์เฟซที่ไดนามิกและสามารถตอบสนองจากเนื้อหาที่เป็นข้อความและภาพ  
- **การผสานทรัพยากร Windows Presentation Foundation (WPF)** – ใช้ทรัพยากรการตีพิมพ์ในแอปพลิเคชัน WPF ได้อย่างไม่มีรอยต่อ  
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การอัตโนมัติ" %}}
- **กระแสงาน EPUB เป็น XAML** – อัตโนมัติการแปลง eBook เป็นไฟล์พร้อมใช้งาน  
- **การสกัดมาร์กอัพแบบอัตโนมัติ** – สกัดองค์ประกอบของ UI อย่างมีประสิทธิภาพสำหรับการใช้งานในการออกแบบ  
- **การสร้าง UI จำนวนมาก** – สร้างไฟล์พร้อมใช้งานสำหรับอินเทอร์เฟซจำนวนมากจากไลบรารีการตีพิมพ์ขนาดใหญ่  
- **การทำงานของแอปพลิเคชันระดับองค์กร** – ผสานการแปลง EPUB เป็น XAML เข้าสู่กระแสการพัฒนาซอฟต์แวร์ที่มีขนาดใหญ่ได้  
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}