---
title: แปลง CGM เป็น IMAGE ผ่าน Java
description: ส่งออกไฟล์ CGM เป็น IMAGE ในแอปพลิเคชัน Java ของคุณโดยไม่ต้องใช้แอปพลิเคชันของบุคคลที่สาม
url_ignore: /th/java/conversion/cgm-to-image/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: TGA DXF IMAGE WMZ JPEG2000 WMF SVGZ  PSD EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง CGM เป็น IMAGE ผ่าน Java" h2="ส่งออกไฟล์ CGM ไปยัง IMAGE ภายในแอปพลิเคชัน Java J2SE, J2EE, J2ME โดยไม่ต้องใช้ Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลงไฟล์ cgm เป็นอิมเมจ IMAGE ใน Java ได้ในสองขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) คุณสามารถส่งออก CGM เป็น JPEG ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API คุณสามารถแสดง JPEG เป็น IMAGE API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ส่งออก CGM เป็น IMAGE ผ่าน Java" %}}
1. เปิดไฟล์ CGM โดยใช้คลาส [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. เริ่มต้นวัตถุคลาส และแสดง CGM เป็น JPEG โดยใช้ [กระบวนการ](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com aspose.pdf.Page-java.io.OutputStream-) วิธี
3. โหลดไฟล์ JPEG โดยใช้คลาส [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. บันทึกเอกสารในรูปแบบ IMAGE โดยใช้ [บันทึก](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) กระบวนการ
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) และรวมไลบรารี่ไว้ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="แปลง CGM เป็น IMAGE ในไฟล์เดียวผ่าน Java" %}}
API ยังอนุญาตให้คุณส่งออกไฟล์ CGM ไปยัง IMAGE เป็นไฟล์เดียว ในการแปลงหน้าทั้งหมด ก่อนอื่น คุณสามารถแสดงเอกสาร CGM ของคุณเป็นไฟล์ TIFF หนึ่งไฟล์ และหลังจากนั้น คุณสามารถส่งออกไฟล์ TIFF ไปยัง IMAGE ได้ คุณสามารถเปิดไฟล์อินพุตได้โดยใช้คลาส [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) และสร้างอ็อบเจ็กต์อุปกรณ์ Resolution, TiffSettings และ TIFF คุณสามารถรับภาพ TIFF เดียวได้โดยใช้ [กระบวนการ](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int- วิธี java.io.OutputStream-) ของคลาส [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) สุดท้าย คุณสามารถโหลดไฟล์ TIFF โดยใช้คลาส [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) และบันทึกเป็นรูปแบบ IMAGE โดยใช้ [save](https://) apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) วิธี  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลง CGM เป็น IMAGE ด้วยลายน้ำผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถส่งออกไฟล์ CGM ไปยัง IMAGE พร้อมลายน้ำในเอกสาร IMAGE ของคุณได้ ในการเพิ่มลายน้ำให้คุณสามารถแปลง CGM เป็น JPEG และเพิ่มลายน้ำได้ก่อน ในการเพิ่มลายน้ำ ให้โหลดไฟล์รูปภาพโดยใช้คลาส [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) สร้างออบเจกต์ของ [กราฟิก](https) ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) และเริ่มต้นด้วยวัตถุ Image สร้าง [Matrix](https://apireference.aspose.com/imaging/java/) ใหม่ com.aspose.imaging/Matrix) และตั้งค่าการแปลและการแปลงเป็นมุมที่ต้องการและเพิ่มลายน้ำโดยใช้ [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) วิธี หลังจากเพิ่มลายน้ำลงในรูปภาพของคุณแล้ว คุณสามารถบันทึก JPEG เป็นรูปแบบ IMAGE ได้ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="แปลงและหมุน CGM เป็นไฟล์ IMAGE ผ่าน Java" %}}
เมื่อใช้ API คุณยังสามารถหมุนอิมเมจ IMAGE ที่ส่งออกได้ตามความต้องการของคุณ วิธี Image.rotateFlip สามารถใช้หมุนภาพได้ 90/180/270 องศา แล้วพลิกภาพในแนวนอนหรือแนวตั้ง ไลบรารีมีวิธีการง่าย ๆ ในการดำเนินการที่ซับซ้อนในขณะที่ห่อหุ้มรายละเอียดที่น่าเกลียดทั้งหมดไว้ คุณสามารถระบุประเภทของการหมุนและพลิกเพื่อใช้กับรูปภาพได้ ในการหมุนและพลิกภาพ คุณสามารถโหลดภาพ JPEG ที่แปลงแล้วโดยใช้คลาส [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) และเรียก Image วิธีrotatorFlipขณะระบุ [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) ที่เหมาะสม 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to-emz/" name="CGM ถึง EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to-tga/" name="CGM ถึง TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to-jpeg2000/" name="CGM ถึง JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to-image/" name="CGM ถึง IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to-psd/" name="CGM ถึง PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to-wmz/" name="CGM ถึง WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to-svgz/" name="CGM ถึง SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to/" name="CGM ถึง" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to-wmf/" name="CGM ถึง WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to-dxf/" name="CGM ถึง DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/cgm-to-dicom/" name="CGM ถึง DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}