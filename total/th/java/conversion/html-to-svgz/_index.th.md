---
title: แปลง HTML เป็น SVGZ ผ่าน Java
description: ส่งออกไฟล์ HTML เป็น SVGZ ในแอปพลิเคชัน Java ของคุณโดยไม่ต้องใช้แอปพลิเคชันของบุคคลที่สาม
url_ignore: /th/java/conversion/html-to-svgz/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: SVGZ
otherformats: EMZ JPEG2000 PSD WMF TGA IMAGE WMZ DXF SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง HTML เป็น SVGZ ผ่าน Java" h2="ส่งออกไฟล์ HTML ไปยัง SVGZ ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME โดยไม่ต้องใช้ Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลงไฟล์ html เป็นอิมเมจ SVGZ ใน Java ได้ในสองขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถส่งออก HTML เป็น JPEG ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API คุณสามารถแสดง JPEG เป็น SVGZ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ส่งออก HTML เป็น SVGZ ผ่าน Java" %}}
1. เปิดไฟล์ HTML โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. เริ่มต้นวัตถุคลาส และแสดง HTML เป็น JPEG โดยใช้ [กระบวนการ](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com aspose.pdf.Page-java.io.OutputStream-) วิธี
3. โหลดไฟล์ JPEG โดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. บันทึกเอกสารในรูปแบบ SVGZ โดยใช้ [บันทึก](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="แปลง HTML เป็น SVGZ ในไฟล์เดียวผ่าน Java" %}}
API ยังอนุญาตให้คุณส่งออกไฟล์ HTML ไปยัง SVGZ เป็นไฟล์เดียว ในการแปลงหน้าทั้งหมด ก่อนอื่น คุณสามารถแสดงเอกสาร HTML ของคุณเป็นไฟล์ TIFF หนึ่งไฟล์ และหลังจากนั้น คุณสามารถส่งออกไฟล์ TIFF ไปยัง SVGZ ได้ คุณสามารถเปิดไฟล์อินพุตได้โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และสร้างอ็อบเจ็กต์อุปกรณ์ Resolution, TiffSettings และ TIFF คุณสามารถรับภาพ TIFF เดียวได้โดยใช้ [กระบวนการ](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- วิธี java.io.OutputStream-) ของคลาส [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) สุดท้าย คุณสามารถโหลดไฟล์ TIFF โดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) และบันทึกเป็นรูปแบบ SVGZ โดยใช้ [save](https://) apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) วิธี  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง HTML เป็น SVGZ ด้วยลายน้ำผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถส่งออกไฟล์ HTML ไปยัง SVGZ พร้อมลายน้ำในเอกสาร SVGZ ของคุณได้ ในการเพิ่มลายน้ำให้คุณสามารถแปลง HTML เป็น JPEG และเพิ่มลายน้ำได้ก่อน ในการเพิ่มลายน้ำ ให้โหลดไฟล์รูปภาพโดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) สร้างออบเจกต์ของ [กราฟิก](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) และเริ่มต้นด้วยวัตถุ Image สร้าง [Matrix](https://reference.aspose.com/imaging/java/) ใหม่ com.aspose.imaging/Matrix) และตั้งค่าการแปลและการแปลงเป็นมุมที่ต้องการและเพิ่มลายน้ำโดยใช้ [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) วิธี หลังจากเพิ่มลายน้ำลงในรูปภาพของคุณแล้ว คุณสามารถบันทึก JPEG เป็นรูปแบบ SVGZ ได้ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลงและหมุน HTML เป็นไฟล์ SVGZ ผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถหมุนอิมเมจ SVGZ ที่ส่งออกได้ตามความต้องการของคุณ วิธี Image.rotateFlip สามารถใช้หมุนภาพได้ 90/180/270 องศา แล้วพลิกภาพในแนวนอนหรือแนวตั้ง ไลบรารีมีวิธีการง่าย ๆ ในการดำเนินการที่ซับซ้อนในขณะที่ห่อหุ้มรายละเอียดที่น่าเกลียดทั้งหมดไว้ คุณสามารถระบุประเภทของการหมุนและพลิกเพื่อใช้กับรูปภาพได้ ในการหมุนและพลิกภาพ คุณสามารถโหลดภาพ JPEG ที่แปลงแล้วโดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) และเรียก Image วิธีrotatorFlipขณะระบุ [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) ที่เหมาะสม 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **HTML เป็น SVGZ (Compressed SVG)** เป็นสิ่งจำเป็นสำหรับการสร้าง **กราฟิกเวกเตอร์ที่มีความยืดหยุ่นและบีบอัด** จากหน้าเว็บ  SVGZ ช่วยรักษาความชัดเจนและความยืดหยุ่นของกราฟิกเวกเตอร์ในขณะลดขนาดไฟล์อย่างมีนัยสำคัญ ทำให้เหมาะสำหรับการออกแบบที่ตอบสนอง, ภาพประกอบพร้อมใช้งานบนเว็บ, และเนื้อหาดิจิทัลที่สามารถแสดงออกมาได้ โดยการแปลงเนื้อหา HTML เป็น SVGZ, องค์กรสามารถปรับปรุงประสิทธิภาพ, ปรับปรุงเวลาโหลด, และจัดการทรัพยากรเวกเตอร์ได้อย่างมีประสิทธิภาพทั่วแพลตฟอร์ม

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}

* **Infographics** – สร้างกราฟิกเวกเตอร์ที่ชัดเจนและกะทัดรัดสำหรับการแสดงข้อมูล
* **Web-ready diagrams** – สร้างแผนภูมิที่ยืดหยุ่นที่ผสานอย่างไม่มีรอยต่อเข้ากับเว็บไซต์
* **การเผยแพร่ที่มีน้ำหนักเบา** – ลดขนาดไฟล์เพื่อการส่งมอบเร็วขึ้นในการตีพิมพ์ดิจิทัล
* **ทรัพยากรภาพที่เหมาะสำหรับมือถือ** – รับรองกราฟิกที่ชัดเจนบนหน้าจอทุกขนาดหรืออุปกรณ์
* **การออกแบบแบบโต้ตอบ** – สนับสนุนการเคลื่อนไหวและการโต้ตอบในขณะรักษาขนาดไฟล์เล็ก

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การใช้งานอัตโนมัติ" %}}

* **ท่อการทำงาน HTML-to-SVGZ** – อัตโนมัติการแปลงเนื้อหาเว็บเป็นกราฟิกเวกเตอร์ที่บีบอัด
* **การบีบอัดเวกเตอร์อัตโนมัติ** – สร้างไฟล์ SVGZ ที่ถูกปรับปรุงอย่างสม่ำเสมอสำหรับการใช้งานบนเว็บและมือถือ
* **กระบวนการทำงานแผนภูมิเป็นก้อน** – ประมวลผลทรัพยากรเวกเตอร์หลายรายการอย่างมีประสิทธิภาพสำหรับโครงการขนาดใหญ่
* **การเผยแพร่ที่มีน้ำหนักเบาระดับองค์กร** – ผสานการสร้าง SVGZ เข้ากับกระบวนการเผยแพร่ดิจิทัลที่สามารถขยายได้

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}