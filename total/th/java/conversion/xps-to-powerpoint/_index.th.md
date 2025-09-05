---
title: การแปลง XPS เป็น Powerpoint ออนไลน์หรือพัฒนาแอปพลิเคชันที่ใช้ Java เพื่อแปลงไฟล์ XPS
description: แอปออนไลน์ฟรีสำหรับแปลงไฟล์ XPS เป็น Powerpoint รหัสไลบรารีการแปลง Java สำหรับเอกสาร XPS 

family: total
platformtag: Java
feature: conversion
informat: XPS
outformat: Powerpoint
otherformats: PPSX POTM POT OTP SWF XAML PPT POTX PPSM PPTM PPS POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แอปแปลง XPS เป็น Powerpoint ออนไลน์และโค้ด Java เพื่อแปลงไฟล์ XPS" h2="พัฒนาแอปพลิเคชั่นการแปลงและส่งออก XPS ที่มีประสิทธิภาพโดยใช้ Java แปลงไฟล์ XPS เดียวหรือหลายไฟล์เป็น Powerpoint และรูปแบบอื่นๆ ผ่านทาง API อัตโนมัติของ Java แปลงไฟล์ XPS ออนไลน์ได้อย่างอิสระผ่านแอปพร้อมดาวน์โหลดทันที" >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="แอปแปลง XPS เป็น Powerpoint ออนไลน์ฟรี" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=pptx&from=xps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ XPS เป็น Powerpoint ออนไลน์โดยใช้แอป" %}}

1. อัพโหลดไฟล์ XPS เพื่อแปลง
1. รอสักครู่หรือมากกว่านั้น ขึ้นอยู่กับขนาดของ XPS
1. คอยดูแถบสถานะการอัปโหลด
1. คลิกปุ่ม "แปลง"
1. XPS จะถูกแปลงเป็นเอกสาร Powerpoint
1. ดาวน์โหลดไฟล์ Powerpoint ที่แปลงแล้ว

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="แปลง XPS เป็น Powerpoint ผ่านทาง Java Automation API" %}}


1. เปิดไฟล์ XPS โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง XPS เป็น PPTX โดยใช้วิธีการ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. บันทึกเอกสารในรูปแบบ POWERPOINT โดยใช้เมธอด [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) และตั้งค่า `Powerpoint` เป็น SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "ff4a1b9329c9c3428525cb1c7b528cc0" "convert-xps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

มีกรณีเพิ่มเติมอีกไม่กี่กรณีสำหรับการบันทึก XPS ไปยัง Powerpoint พร้อมด้วยฟีเจอร์อื่นๆ เช่น ข้อกำหนดการแปลง, เปิดไฟล์ XPS ที่เข้ารหัสผ่าน Java

{{% blocks/products/pf/feature-page-code %}}


```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);    
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>พัฒนาแอปพลิเคชันการแปลงไฟล์ XPS โดยใช้ Java</h2>

ต้องการพัฒนาแอปพลิเคชันซอฟต์แวร์ที่ใช้ Java เพื่อบันทึกและส่งออกไฟล์ XPS ไปยังเอกสาร Powerpoint ได้อย่างง่ายดายหรือไม่ ด้วย [Aspose.Total for Java](https://products.aspose.com/total/th/java/) นักพัฒนา Java ทุกคนสามารถรวมโค้ด API ข้างต้นเพื่อเขียนโปรแกรมแอปพลิเคชันการแปลงไฟล์ในรูปแบบต่างๆ รวมถึง Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, ไฟล์อีเมล, รูปภาพ (JPG, PNG, BMP, GIF) และรูปแบบอื่นๆ ไลบรารี Java อันทรงพลังสำหรับการแปลงเอกสาร รองรับรูปแบบยอดนิยมมากมาย รวมถึงรูปแบบ XPS ในการส่งออกและเรนเดอร์เอกสารเป็นรูปแบบอื่น โปรแกรมเมอร์สามารถใช้ API ย่อย Aspose.Total for Java ได้ ซึ่งได้แก่ [Aspose.Words for Java](https://products.aspose.com/words/th/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/th/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/th/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/th/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/th/java/) และอื่นๆ อีกมากมาย<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ไลบรารีการแปลง XPS สำหรับ Java" %}}

มีตัวเลือกอื่นในการรวม Aspose.Total for Java เข้ากับระบบของคุณ กรุณาเลือกสิ่งที่ตรงกับความต้องการของคุณและปฏิบัติตามคำแนะนำทีละขั้นตอน:<br /><br />

- ใช้ Aspose.Total for Java โดยตรงจากโปรเจ็กต์ที่ใช้ Maven และรวม API ย่อยที่เกี่ยวข้องใน pom.xml
- อีกวิธีหนึ่งคือสามารถได้รับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="การบันทึก XPS ไปยังข้อกำหนดแอป Powerpoint" %}}

ระบบปฏิบัติการใดๆ ที่สามารถรัน Java Runtime Environment (JRE) ได้ ก็สามารถรัน Aspose.Total for Java ได้ รายการต่อไปนี้เป็นระบบปฏิบัติการที่รองรับเป็นส่วนใหญ่ แต่ไม่ใช่ทั้งหมด <br /><br />
- ไมโครซอฟต์ วินโดวส์
- Linux : Ubuntu, OpenSUSE, CentOS และอื่นๆ
- macOS : 10.9 (Mavericks) และใหม่กว่า
- มือถือ : Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}