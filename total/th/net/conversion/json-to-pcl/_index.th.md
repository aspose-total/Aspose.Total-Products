---
title: แปลงรูปแบบ JSON เป็น PCL ผ่าน .NET
description: แยก JSON เป็น PCL ใน C# โดยไม่ต้องใช้ Microsoft Word
url_ignore: /th/net/conversion/json-to-pcl/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PCL
otherformats: PS DOC DOTX DOCM RTF MOBI EPUB PCL OTT WORD ODT FLATOPC WORDML DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น PCL ผ่าน C#" h2="C# API เพื่อแยก JSON เป็น PCL โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถแยกวิเคราะห์ JSON เป็น PCL ภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ได้ด้วยวิธีง่ายๆ สองแบบ ขั้นตอน ประการแรก ด้วยการใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) คุณสามารถส่งออก JSON เป็น PDF หลังจากนั้น เมื่อใช้ [Aspose.Words for .NET](https://products.aspose.com/words/net/) คุณจะสามารถแปลง PDF เป็น PCL ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น PCL ผ่าน C#" %}}
1. สร้าง [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) วัตถุใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. นำเข้าไฟล์ JSON ไปยังเวิร์กชีตโดยใช้คลาส [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) และ [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) เป็น PDF
3. โหลดเอกสาร PDF โดยใช้คลาส [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. บันทึกเอกสารในรูปแบบ PCL โดยใช้วิธี [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น PCL ผ่าน C#" %}}
ขณะแยกวิเคราะห์ JSON เป็น PCL คุณยังตั้งค่าตัวเลือกเลย์เอาต์สำหรับ JSON ได้โดยใช้ [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่า null ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แยกรูปแบบ JSON เป็น PCL ด้วย Watermark" %}}
การใช้ API คุณสามารถแปลง JSON เป็น PCL ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร PCL ของคุณ ก่อนอื่นให้แยกไฟล์ JSON เป็น PDF และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PDF ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/net/aspose.words/document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่าคุณสมบัติ, โทรวิธี Watermark.SetText และส่งข้อความลายน้ำและวัตถุของ TextWatermarkOptions หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปที่ PCL 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}