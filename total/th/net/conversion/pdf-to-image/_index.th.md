---
title: แปลง PDF เป็น IMAGE ผ่าน C# API
description: ส่งออก PDF เป็น IMAGE ในแอปพลิเคชัน .NET ของคุณโดยไม่ต้องใช้แอปพลิเคชันของบุคคลที่สาม
url_ignore: /th/net/conversion/pdf-to-image/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: IMAGE
otherformats: JPEG2000 EMZ  WMZ TGA PSD DXF WMF SVGZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงไฟล์ PDF เป็น IMAGE ผ่าน C#" h2="ส่งออก PDF เป็น IMAGE ภายในแอปพลิเคชัน .NET โดยไม่ต้องใช้ Adobe<sup>&reg;</sup> Acrobat Reader หรือแอปพลิเคชันบุคคลที่สามอื่นๆ" >}}

{{% blocks/products/pf/feature-page-summary %}}
การใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถส่งออก PDF ไปยังรูปภาพ IMAGE ภายในแอปพลิเคชัน .NET ได้ง่ายๆ ในสองขั้นตอนง่ายๆ ก่อนอื่น ด้วยการใช้ [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณสามารถส่งออก PDF เป็น JPEG ได้ หลังจากนั้น ด้วยการใช้ [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API คุณสามารถแปลง JPEG เป็น IMAGE ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงไฟล์ PDF เป็น IMAGE ผ่าน .NET" %}}
1. เปิดไฟล์ PDF โดยใช้คลาส [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. เริ่มต้น [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) วัตถุคลาสและแสดง PDF เป็น JPEG โดยใช้ [กระบวนการ](https://apireference.aspose com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) วิธี
3. โหลดไฟล์ JPEG โดยใช้คลาส [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. บันทึกเอกสารในรูปแบบ IMAGE โดยใช้วิธี [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="แปลงไฟล์ PDF เป็น IMAGE ในไฟล์เดียวผ่าน C#" %}}
เมื่อใช้ API คุณยังสามารถแปลงไฟล์ PDF เป็น IMAGE เป็นไฟล์รูปภาพเดียวได้ ในการแปลงหน้าทั้งหมด ก่อนอื่นคุณสามารถแสดงเอกสาร PDF ของคุณเป็นไฟล์ TIFF หนึ่งไฟล์ และหลังจากนั้นคุณสามารถส่งออกไฟล์ TIFF ไปยัง IMAGE ได้ คุณสามารถเปิดไฟล์อินพุตได้โดยใช้คลาส [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) และสร้างอ็อบเจ็กต์อุปกรณ์ Resolution, TiffSettings และ TIFF คุณสามารถรับรูปภาพ TIFF เดียวได้โดยใช้วิธี [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) ของวิธี [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) คลาส สุดท้าย คุณสามารถโหลดไฟล์ TIFF โดยใช้คลาส [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
และบันทึกเป็นรูปแบบ IMAGE โดยใช้วิธี [บันทึก](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}C#

{{% blocks/products/pf/feature-page-section  h2="แปลงและหมุนไฟล์ PDF เป็น IMAGE ผ่าน C#" %}}
เมื่อใช้ API คุณยังสามารถหมุนอิมเมจ IMAGE ที่ส่งออกได้ตามความต้องการของคุณ วิธี Image.RotateFlip สามารถใช้หมุนภาพได้ 90/180/270 องศา แล้วพลิกภาพในแนวนอนหรือแนวตั้ง คุณสามารถระบุประเภทของการหมุนและพลิกเพื่อใช้กับรูปภาพได้ ในการหมุนและพลิกภาพ คุณสามารถโหลดภาพ JPEG ที่แปลงแล้วโดยใช้วิธีการจากโรงงานที่แสดงโดยคลาส [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) และเรียก Image วิธี .RotateFlip ขณะระบุ [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) ที่เหมาะสม 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}