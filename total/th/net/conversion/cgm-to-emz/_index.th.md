---
title: แปลง CGM เป็น EMZ ผ่าน C# API
description: ส่งออก CGM เป็น EMZ ในแอปพลิเคชัน .NET ของคุณโดยไม่ต้องใช้แอปพลิเคชันของบุคคลที่สาม
url: /th/net/conversion/cgm-to-emz/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: EMZ
otherformats: SVGZ WMF PSD EMZ WMZ TGA JPEG2000 IMAGE DXF  DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงไฟล์ CGM เป็น EMZ ผ่าน C#" h2="ส่งออก CGM เป็น EMZ ภายในแอปพลิเคชัน .NET โดยไม่ต้องใช้ Adobe<sup>&reg;</sup> Acrobat Reader หรือแอปพลิเคชันบุคคลที่สามอื่นๆ" >}}

{{% blocks/products/pf/feature-page-summary %}}
การใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถส่งออก CGM ไปยังรูปภาพ EMZ ภายในแอปพลิเคชัน .NET ได้ง่ายๆ ในสองขั้นตอนง่ายๆ ก่อนอื่น ด้วยการใช้ [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณสามารถส่งออก CGM เป็น JPEG ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API คุณสามารถแปลง JPEG เป็น EMZ ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ CGM เป็น EMZ ผ่าน .NET" %}}
1. เปิดไฟล์ CGM โดยใช้คลาส [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. เริ่มต้น [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) วัตถุคลาสและแสดง CGM เป็น JPEG โดยใช้ [กระบวนการ](https://apireference.aspose com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) วิธี
3. โหลดไฟล์ JPEG โดยใช้คลาส [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. บันทึกเอกสารในรูปแบบ EMZ โดยใช้วิธี [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="แปลงไฟล์ CGM เป็น EMZ ในไฟล์เดียวผ่าน C #" %}}
เมื่อใช้ API คุณยังสามารถแปลงไฟล์ CGM เป็น EMZ เป็นไฟล์รูปภาพเดียวได้ ในการแปลงหน้าทั้งหมด ก่อนอื่นคุณสามารถแสดงเอกสาร CGM ของคุณเป็นไฟล์ TIFF หนึ่งไฟล์ และหลังจากนั้นคุณสามารถส่งออกไฟล์ TIFF ไปยัง EMZ ได้ คุณสามารถเปิดไฟล์อินพุตได้โดยใช้คลาส [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) และสร้างอ็อบเจ็กต์อุปกรณ์ Resolution, TiffSettings และ TIFF คุณสามารถรับรูปภาพ TIFF เดียวได้โดยใช้วิธี [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) ของวิธี [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) คลาส สุดท้าย คุณสามารถโหลดไฟล์ TIFF โดยใช้คลาส [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
และบันทึกเป็นรูปแบบ EMZ โดยใช้วิธี [บันทึก](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}C#

{{% blocks/products/pf/feature-page-section  h2="แปลงและหมุนไฟล์ CGM เป็น EMZ ผ่าน C #" %}}
เมื่อใช้ API คุณยังสามารถหมุนอิมเมจ EMZ ที่ส่งออกได้ตามความต้องการของคุณ วิธี Image.RotateFlip สามารถใช้หมุนภาพได้ 90/180/270 องศา แล้วพลิกภาพในแนวนอนหรือแนวตั้ง คุณสามารถระบุประเภทของการหมุนและพลิกเพื่อใช้กับรูปภาพได้ ในการหมุนและพลิกภาพ คุณสามารถโหลดภาพ JPEG ที่แปลงแล้วโดยใช้วิธีการจากโรงงานที่แสดงโดยคลาส [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) และเรียก Image วิธี .RotateFlip ขณะระบุ [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) ที่เหมาะสม 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

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