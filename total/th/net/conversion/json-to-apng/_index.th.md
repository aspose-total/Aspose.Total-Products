---
title: แปลงรูปแบบ JSON เป็น APNG ผ่าน .NET
description: แยก JSON เป็น APNG ใน C# โดยไม่ต้องใช้การพึ่งพาบุคคลที่สาม
url_ignore: /th/net/conversion/json-to-apng/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: APNG
otherformats: WMZ DICOM PSD JPEG2000 TGA EMZ SVGZ WMF IMAGE DXF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น APNG ผ่าน C#" h2="C# API เพื่อแยก JSON เป็น APNG โดยไม่ต้องใช้การพึ่งพาบุคคลที่สาม" >}}

{{% blocks/products/pf/feature-page-summary %}}
เมื่อใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถแยกวิเคราะห์ JSON เป็น APNG ภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ได้สองแบบง่ายๆ ขั้นตอน ประการแรก โดยใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) คุณสามารถส่งออก JSON เป็น JPEG หลังจากนั้น เมื่อใช้ [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) คุณจะสามารถแปลง JPEG เป็น APNG
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น APNG ผ่าน C#" %}}
1. สร้าง [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) วัตถุใหม่และอ่านข้อมูล JSON จากไฟล์
2. แปลง JSON เป็น JPEG โดยใช้วิธี [บันทึก](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. โหลดเอกสาร JPEG โดยใช้คลาส [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. บันทึกเอกสารในรูปแบบ APNG โดยใช้วิธี [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น APNG ผ่าน C#" %}}
ขณะแยกวิเคราะห์ JSON เป็น APNG คุณยังตั้งค่าตัวเลือกเลย์เอาต์สำหรับ JSON ได้โดยใช้ [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่า null ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แยกวิเคราะห์รูปแบบ JSON เป็น APNG ด้วยลายน้ำ" %}}
เมื่อใช้ API คุณยังสามารถแปลง JSON เป็น APNG ด้วยลายน้ำในเอกสาร APNG ของคุณ ในการเพิ่มลายน้ำ ก่อนอื่นคุณสามารถแสดงเอกสาร JSON ของคุณเป็น JPEG และเพิ่มลายน้ำลงไปได้ ในการสาธิตการทำงาน คุณสามารถโหลดภาพ JPEG ที่แปลงแล้ว เพิ่มการแปลงโดยใช้วัตถุของคลาส Matrix และวาดสตริงเป็นลายน้ำบนพื้นผิวของภาพโดยใช้[กราฟิก](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) คลาส' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) วิธี หลังจากเพิ่มลายน้ำลงไปแล้ว คุณสามารถบันทึกไฟล์ JPEG เป็นรูปแบบ APNG ได้ ด้านล่างนี้คือตัวอย่างโค้ดที่สาธิตวิธีการเพิ่มลายน้ำในแนวทแยงลงในเอกสารของคุณ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}