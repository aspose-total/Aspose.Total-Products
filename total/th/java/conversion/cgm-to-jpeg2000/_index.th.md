---
title: แปลง CGM เป็น JPEG2000 ผ่าน Java
description: ส่งออกไฟล์ CGM เป็น JPEG2000 ในแอปพลิเคชัน Java ของคุณโดยไม่ต้องใช้แอปพลิเคชันของบุคคลที่สาม
url_ignore: /th/java/conversion/cgm-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: WMF  TGA DXF IMAGE WMZ JPEG2000 PSD SVGZ EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง CGM เป็น JPEG2000 ผ่าน Java" h2="ส่งออกไฟล์ CGM ไปยัง JPEG2000 ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME โดยไม่ต้องใช้ Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลงไฟล์ cgm เป็นอิมเมจ JPEG2000 ใน Java ได้ในสองขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถส่งออก CGM เป็น JPEG ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API คุณสามารถแสดง JPEG เป็น JPEG2000 API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ส่งออก CGM เป็น JPEG2000 ผ่าน Java" %}}
1. เปิดไฟล์ CGM โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. เริ่มต้นวัตถุคลาส และแสดง CGM เป็น JPEG โดยใช้ [กระบวนการ](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com aspose.pdf.Page-java.io.OutputStream-) วิธี
3. โหลดไฟล์ JPEG โดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. บันทึกเอกสารในรูปแบบ JPEG2000 โดยใช้ [บันทึก](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="แปลง CGM เป็น JPEG2000 ในไฟล์เดียวผ่าน Java" %}}
API ยังอนุญาตให้คุณส่งออกไฟล์ CGM ไปยัง JPEG2000 เป็นไฟล์เดียว ในการแปลงหน้าทั้งหมด ก่อนอื่น คุณสามารถแสดงเอกสาร CGM ของคุณเป็นไฟล์ TIFF หนึ่งไฟล์ และหลังจากนั้น คุณสามารถส่งออกไฟล์ TIFF ไปยัง JPEG2000 ได้ คุณสามารถเปิดไฟล์อินพุตได้โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และสร้างอ็อบเจ็กต์อุปกรณ์ Resolution, TiffSettings และ TIFF คุณสามารถรับภาพ TIFF เดียวได้โดยใช้ [กระบวนการ](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- วิธี java.io.OutputStream-) ของคลาส [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) สุดท้าย คุณสามารถโหลดไฟล์ TIFF โดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) และบันทึกเป็นรูปแบบ JPEG2000 โดยใช้ [save](https://) apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) วิธี  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง CGM เป็น JPEG2000 ด้วยลายน้ำผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถส่งออกไฟล์ CGM ไปยัง JPEG2000 พร้อมลายน้ำในเอกสาร JPEG2000 ของคุณได้ ในการเพิ่มลายน้ำให้คุณสามารถแปลง CGM เป็น JPEG และเพิ่มลายน้ำได้ก่อน ในการเพิ่มลายน้ำ ให้โหลดไฟล์รูปภาพโดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) สร้างออบเจกต์ของ [กราฟิก](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) และเริ่มต้นด้วยวัตถุ Image สร้าง [Matrix](https://reference.aspose.com/imaging/java/) ใหม่ com.aspose.imaging/Matrix) และตั้งค่าการแปลและการแปลงเป็นมุมที่ต้องการและเพิ่มลายน้ำโดยใช้ [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) วิธี หลังจากเพิ่มลายน้ำลงในรูปภาพของคุณแล้ว คุณสามารถบันทึก JPEG เป็นรูปแบบ JPEG2000 ได้ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลงและหมุน CGM เป็นไฟล์ JPEG2000 ผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถหมุนอิมเมจ JPEG2000 ที่ส่งออกได้ตามความต้องการของคุณ วิธี Image.rotateFlip สามารถใช้หมุนภาพได้ 90/180/270 องศา แล้วพลิกภาพในแนวนอนหรือแนวตั้ง ไลบรารีมีวิธีการง่าย ๆ ในการดำเนินการที่ซับซ้อนในขณะที่ห่อหุ้มรายละเอียดที่น่าเกลียดทั้งหมดไว้ คุณสามารถระบุประเภทของการหมุนและพลิกเพื่อใช้กับรูปภาพได้ ในการหมุนและพลิกภาพ คุณสามารถโหลดภาพ JPEG ที่แปลงแล้วโดยใช้คลาส [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) และเรียก Image วิธีrotatorFlipขณะระบุ [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) ที่เหมาะสม 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Converting CGM files to JPEG2000 สร้างการเก็บภาพความละเอียดสูงด้วยการบีบอัดขั้นสูง ทำให้เหมาะสำหรับการเก็บถาวรกราฟิกทางเทคนิคและภูมิสเปซ. JPEG 2000 สนับสนุนการรักษาคุณภาพที่ดีกว่า ทำให้เป็นตัวเลือกที่ดีสำหรับอุตสาหกรรมที่ต้องการรายละเอียดที่แม่นยำพร้อมกับขนาดไฟล์ที่ลดลง.

## ✅ กรณีการใช้งานหลัก
- เก็บถาวรความละเอียดสูงของแบบแปลนวิศวกรรมหรือสถาปัตยกรรม
- การทำงาน GIS และการทำงานแผนที่ที่ต้องการการเก็บข้อมูลที่มีประสิทธิภาพและละเอียด
- การสตรีมกราฟิกทางเทคนิคที่ปรับแล้วให้เหมาะสำหรับทีมระยะไกล

## ⚙️ สถานการณ์การอัตโนมัติ
- เครื่องมือภาพภูมิศาสตร์ที่ใช้ Java สำหรับการสร้าง JPEG2000 โดยอัตโนมัติ
- คลังข้อมูลองค์กรที่มีความต้องการในการเก็บถาวรคุณภาพสูง
- บริการภาพบนคลาวด์ที่มีขนาดยืดหยุ่นสำหรับการกระจายข้อมูลที่มีประสิทธิภาพ
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}