---
title: แปลงรูปแบบ JSON เป็น POT ผ่าน .NET
description: แยก JSON เป็น POT ใน C# โดยไม่ต้องใช้ Microsoft PowerPoint
url_ignore: /th/net/conversion/json-to-pot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POT
otherformats: POTM PPT PPTM PPSM POT PPSX POWERPOINT OTP PPS POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงรูปแบบ JSON เป็น POT ผ่าน C#" h2="C# API เพื่อแยก JSON เป็น POT โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง JSON เป็น POT ภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ได้ในสองขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) คุณสามารถแยก JSON เป็น PPTX หลังจากนั้น ด้วยการใช้ [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) คุณจะสามารถแปลง PPTX เป็น POT ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for .NET](https://products.aspose.com/total/net/)
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น POT ผ่าน C#" %}}
1. สร้าง [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) วัตถุใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. นำเข้าไฟล์ JSON ไปยังเวิร์กชีตโดยใช้คลาส [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) และ [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) เป็น PPTX
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. บันทึกเอกสารในรูปแบบ POT โดยใช้วิธี [บันทึก](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น POT ผ่าน C#" %}}
ขณะแยกวิเคราะห์ JSON เป็น POT คุณยังตั้งค่าตัวเลือกเลย์เอาต์สำหรับรูปแบบ JSON ได้โดยใช้ [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) ช่วยให้คุณสามารถประมวลผลอาร์เรย์เป็นตาราง ละเว้นค่าว่าง ละเว้นชื่ออาร์เรย์ ละเว้นชื่ออ็อบเจ็กต์ แปลงสตริงเป็นตัวเลขหรือวันที่ กำหนดรูปแบบวันที่และตัวเลข และกำหนดรูปแบบชื่อ ตัวเลือกทั้งหมดเหล่านี้ช่วยให้คุณสามารถนำเสนอข้อมูลได้ตามความต้องการของคุณ ข้อมูลโค้ดต่อไปนี้แสดงวิธีตั้งค่าตัวเลือกเลย์เอาต์  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลงรูปแบบ JSON เป็น POT ด้วย Watermark" %}}
เมื่อใช้ API คุณจะแปลง JSON เป็น POT ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร POT ของคุณ ก่อนอื่นให้แยก JSON เป็น PPTX และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PPTX ที่สร้างขึ้นใหม่โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) เลือกการนำเสนอต้นแบบ เพิ่มประเภทรูปร่างโดยใช้ AddAutoShape และเพิ่มข้อความลายน้ำโดยใช้ AddTextFrame หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปยัง POT ได้ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}