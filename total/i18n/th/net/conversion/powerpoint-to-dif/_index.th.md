---
title: แปลง POWERPOINT เป็น DIF ผ่าน C#
description: แปลง POWERPOINT เป็น DIF ใน C# โดยไม่ต้องใช้ Microsoft Excel หรือ Powerpoint
url: /th/net/conversion/powerpoint-to-dif/
family: total
platformtag: net
feature: conversion
informat: POWERPOINT
outformat: DIF
otherformats: XLS FODS XLSM XLTX SXC XLSX EXCEL TSV XLTM XLSB XLAM DIF MARKDOWN MHTML ODS XLT DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง POWERPOINT เป็น DIF ผ่าน C#" h2=".NET API สำหรับการแปลง POWERPOINT เป็น DIF โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถแปลงไฟล์ POWERPOINT เป็น DIF ภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ได้เป็นสองส่วน ขั้นตอนง่ายๆ ประการแรก ด้วยการใช้ [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) คุณสามารถส่งออก POWERPOINT เป็น HTML หลังจากนั้น การใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API จะช่วยให้คุณแปลง HTML เป็น DIF ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง POWERPOINT เป็น DIF ผ่าน C#" %}}
1. เปิดไฟล์ POWERPOINT โดยใช้คลาส [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
2. ส่งออก POWERPOINT เป็น HTML โดยใช้วิธีการ [บันทึก](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. บันทึกเอกสารเป็น DIF โดยใช้วิธี [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="แปลง Protected POWERPOINT เป็น DIF ผ่าน C #" %}}
ขณะแปลงไฟล์ POWERPOINT เป็น DIF หากเอกสาร POWERPOINT ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น DIF ได้โดยไม่ต้องถอดรหัสลับเอกสาร เมื่อเอกสารของคุณได้รับการป้องกันด้วยรหัสผ่าน แสดงว่ามีการบังคับใช้ข้อจำกัดบางประการในการนำเสนอ ต้องป้อนรหัสผ่านเพื่อลบข้อจำกัด การนำเสนอที่มีการป้องกันด้วยรหัสผ่านถือเป็นการนำเสนอที่ถูกล็อค API อนุญาตให้คุณเปิดเอกสารที่เข้ารหัสโดยส่งรหัสผ่านที่ถูกต้องในออบเจกต์ LoadOptions  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}C#

{{% blocks/products/pf/feature-page-section  h2="แปลง POWERPOINT เป็น DIF ด้วยลายน้ำผ่าน C #" %}}
ขณะแปลงไฟล์ POWERPOINT เป็น DIF คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ DIF เอาต์พุตของคุณได้ ในการเพิ่มลายน้ำ คุณสามารถสร้างวัตถุสมุดงานใหม่และเปิดเอกสาร HTML ที่แปลงแล้ว เลือกแผ่นงานผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน AddTextEffect หลังจากนั้น คุณสามารถบันทึกเอกสาร HTML ของคุณเป็น DIF ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-fods/" name="POWERPOINT ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-xltm/" name="POWERPOINT ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-xlt/" name="POWERPOINT ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-xlam/" name="POWERPOINT ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-markdown/" name="POWERPOINT ถึง MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-excel/" name="POWERPOINT ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-mhtml/" name="POWERPOINT ถึง MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-xlsb/" name="POWERPOINT ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-ods/" name="POWERPOINT ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-sxc/" name="POWERPOINT ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-xls/" name="POWERPOINT ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-xltx/" name="POWERPOINT ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-xlsx/" name="POWERPOINT ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-tsv/" name="POWERPOINT ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-dif/" name="POWERPOINT ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-xlsm/" name="POWERPOINT ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-doc/" name="POWERPOINT ถึง DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-docx/" name="POWERPOINT ถึง DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-docm/" name="POWERPOINT ถึง DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-dot/" name="POWERPOINT ถึง DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-dotm/" name="POWERPOINT ถึง DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-dotx/" name="POWERPOINT ถึง DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-odt/" name="POWERPOINT ถึง ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-ott/" name="POWERPOINT ถึง OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-rtf/" name="POWERPOINT ถึง RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-word/" name="POWERPOINT ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-wordml/" name="POWERPOINT ถึง WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-text/" name="POWERPOINT ถึง TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/powerpoint-to-flatopx/" name="POWERPOINT ถึง FLAถึงPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}