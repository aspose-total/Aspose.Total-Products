---
title: แปลง HTML เป็น TGA ผ่าน Java
description: ส่งออกไฟล์ HTML เป็น TGA ในแอปพลิเคชัน Java ของคุณโดยไม่ต้องใช้แอปพลิเคชันของบุคคลที่สาม
url_ignore: /th/java/conversion/html-to-tga/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: TGA
otherformats: WMZ DXF IMAGE JPEG2000 EMZ SVGZ WMF TGA PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง HTML เป็น TGA ผ่าน Java" h2="ส่งออกไฟล์ HTML ไปยัง TGA ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME โดยไม่ต้องใช้ Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลงไฟล์ html เป็นอิมเมจ TGA ใน Java ได้ในสองขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถส่งออก HTML เป็น JPEG ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API คุณสามารถแสดง JPEG เป็น TGA API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ส่งออก HTML เป็น TGA ผ่าน Java" %}}
1. เปิดไฟล์ HTML โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. เริ่มต้นวัตถุคลาส และแสดง HTML เป็น JPEG โดยใช้ [กระบวนการ](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com aspose.pdf.Page-java.io.OutputStream-) วิธี
3. โหลดไฟล์ JPEG โดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. บันทึกเอกสารในรูปแบบ TGA โดยใช้ [บันทึก](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="แปลง HTML เป็น TGA ในไฟล์เดียวผ่าน Java" %}}
API ยังอนุญาตให้คุณส่งออกไฟล์ HTML ไปยัง TGA เป็นไฟล์เดียว ในการแปลงหน้าทั้งหมด ก่อนอื่น คุณสามารถแสดงเอกสาร HTML ของคุณเป็นไฟล์ TIFF หนึ่งไฟล์ และหลังจากนั้น คุณสามารถส่งออกไฟล์ TIFF ไปยัง TGA ได้ คุณสามารถเปิดไฟล์อินพุตได้โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และสร้างอ็อบเจ็กต์อุปกรณ์ Resolution, TiffSettings และ TIFF คุณสามารถรับภาพ TIFF เดียวได้โดยใช้ [กระบวนการ](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- วิธี java.io.OutputStream-) ของคลาส [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) สุดท้าย คุณสามารถโหลดไฟล์ TIFF โดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) และบันทึกเป็นรูปแบบ TGA โดยใช้ [save](https://) apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) วิธี  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง HTML เป็น TGA ด้วยลายน้ำผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถส่งออกไฟล์ HTML ไปยัง TGA พร้อมลายน้ำในเอกสาร TGA ของคุณได้ ในการเพิ่มลายน้ำให้คุณสามารถแปลง HTML เป็น JPEG และเพิ่มลายน้ำได้ก่อน ในการเพิ่มลายน้ำ ให้โหลดไฟล์รูปภาพโดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) สร้างออบเจกต์ของ [กราฟิก](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) และเริ่มต้นด้วยวัตถุ Image สร้าง [Matrix](https://reference.aspose.com/imaging/java/) ใหม่ com.aspose.imaging/Matrix) และตั้งค่าการแปลและการแปลงเป็นมุมที่ต้องการและเพิ่มลายน้ำโดยใช้ [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) วิธี หลังจากเพิ่มลายน้ำลงในรูปภาพของคุณแล้ว คุณสามารถบันทึก JPEG เป็นรูปแบบ TGA ได้ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลงและหมุน HTML เป็นไฟล์ TGA ผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถหมุนอิมเมจ TGA ที่ส่งออกได้ตามความต้องการของคุณ วิธี Image.rotateFlip สามารถใช้หมุนภาพได้ 90/180/270 องศา แล้วพลิกภาพในแนวนอนหรือแนวตั้ง ไลบรารีมีวิธีการง่าย ๆ ในการดำเนินการที่ซับซ้อนในขณะที่ห่อหุ้มรายละเอียดที่น่าเกลียดทั้งหมดไว้ คุณสามารถระบุประเภทของการหมุนและพลิกเพื่อใช้กับรูปภาพได้ ในการหมุนและพลิกภาพ คุณสามารถโหลดภาพ JPEG ที่แปลงแล้วโดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) และเรียก Image วิธีrotatorFlipขณะระบุ [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) ที่เหมาะสม 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **HTML เป็น TGA (Truevision Graphics Adapter)** เป็นสิ่งจำเป็นสำหรับสร้าง **กราฟิกเราสเตอร์คุณภาพสูง** จากเนื้อหาเว็บ ไฟล์ TGA สามารถรักษาความละเอียดของสีและรายละเอียดของภาพได้ดี เหมาะสำหรับกราฟิกอาชีพ การแสดงภาพ 3 มิติ และสื่อพร้อมสำหรับการพิมพ์ โดยการแปลง HTML เป็น TGA องค์กรสามารถให้การสร้างภาพที่แม่นยำสำหรับเกมมิ่ง การออกแบบ และการเผยแพร่งาน พร้อมรักษาความเข้ากันได้กับซอฟต์แวร์สร้างสรรค์ขั้นสูง

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}

* **กระบวนการทำงานในอุตสาหกรรมเกมมิ่ง** – แปลงทรัพยากรบนเว็บเป็นกราฟิกคุณภาพสูงสำหรับเกมและการจำลอง
* **การแสดงภาพสามมิติ** – สร้างภาพราสเตอร์ที่ละเอียดเหมาะสำหรับการจำลองและการเรนเดอร์
* **การพิมพ์สื่อดิจิทัล** – สร้างเนื้อหาภาพที่ชัดเจนสำหรับนิตยสารออนไลน์ หนังสืออิเล็กทรอนิกส์ และสื่อโต้ตอบ
* **ทรัพยากรออกแบบกราฟิก** – ผลิตกราฟิกราสเตอร์ที่สามารถแก้ไขได้สำหรับโครงการออกแบบอาชีพ
* **สื่อพิมพ์** – ให้การสร้างสีที่แม่นยำและผลลัพธ์ความละเอียดสูงสำหรับการพิมพ์สื่อ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}

* **กระบวนการทำงาน HTML เป็น TGA** – อัตโนมัติการแปลงเนื้อหาเว็บเป็นไฟล์ราสเตอร์คุณภาพสูง
* **การเรนเดอร์ราสเตอร์อัตโนมัติ** – สร้างภาพ TGA ที่มีสีและรายละเอียดแม่นยำอย่างต่อเนื่อง
* **การแปลงทรัพยากรเป็นกลุ่ม** – ประมวลผลหลายหน้าเว็บหรือองค์ประกอบการออกแบบได้อย่างมีประสิทธิภาพ
* **การพิมพ์สื่อระดับองค์กร** – ผสานการสร้าง TGA เข้ากับกระบวนการผลิตกราฟิกขนาดใหญ่และการเผยแพร่งาน

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}