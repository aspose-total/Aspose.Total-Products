---
title: แปลงรูปแบบ JSON เป็น DOCM ผ่าน .NET
description: แยก JSON เป็น DOCM ใน C# โดยไม่ต้องใช้ Microsoft Word
url: /th/net/conversion/json-to-docm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOCM
otherformats: DOT EPUB PCL WORDML OTT RTF DOTX PS MOBI ODT WORD FLATOPC DOC DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น DOCM ผ่าน C#" h2="C# API เพื่อแยก JSON เป็น DOCM โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถแยกวิเคราะห์ JSON เป็น DOCM ภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ได้ด้วยวิธีง่ายๆ สองแบบ ขั้นตอน ประการแรก ด้วยการใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) คุณสามารถส่งออก JSON เป็น PDF หลังจากนั้น เมื่อใช้ [Aspose.Words for .NET](https://products.aspose.com/words/net/) คุณจะสามารถแปลง PDF เป็น DOCM ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น DOCM ผ่าน C#" %}}
1. สร้าง [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) วัตถุใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. นำเข้าไฟล์ JSON ไปยังเวิร์กชีตโดยใช้คลาส [JsonUtility](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) และ [Save](https://apireference.aspose.com/ cells/net/aspose.cells.workbook/save/methods/4) เป็น PDF
3. โหลดเอกสาร PDF โดยใช้คลาส [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. บันทึกเอกสารในรูปแบบ DOCM โดยใช้วิธี [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น DOCM ผ่าน C #" %}}
ขณะแยกวิเคราะห์ JSON เป็น DOCM คุณยังตั้งค่าตัวเลือกเลย์เอาต์สำหรับ JSON ได้โดยใช้ [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่า null ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดวันที่และรูปแบบตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แยกรูปแบบ JSON เป็น DOCM ด้วย Watermark" %}}
การใช้ API คุณสามารถแปลง JSON เป็น DOCM ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร DOCM ของคุณ ก่อนอื่นให้แยกไฟล์ JSON เป็น PDF และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PDF ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://apireference.aspose.com/words/net/aspose.words/document) สร้างอินสแตนซ์ของ TextWatermarkOptions และตั้งค่าคุณสมบัติ , โทรวิธี Watermark.SetText และส่งข้อความลายน้ำและวัตถุของ TextWatermarkOptions หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปที่ DOCM 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-ott/" name="JSON ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-flatopc/" name="JSON ถึง FLAถึงPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-ps/" name="JSON ถึง PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-dotx/" name="JSON ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-rtf/" name="JSON ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-wordml/" name="JSON ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-odt/" name="JSON ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-word/" name="JSON ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-epub/" name="JSON ถึง EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-doc/" name="JSON ถึง DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-dot/" name="JSON ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-pcl/" name="JSON ถึง PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-mobi/" name="JSON ถึง MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/json-to-docm/" name="JSON ถึง DOCM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}