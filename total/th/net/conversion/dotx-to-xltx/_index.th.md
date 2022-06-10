---
title: .NET API เพื่อแปลง DOTX เป็น XLTX
description: C# API เพื่อแปลง DOTX เป็น XLTX โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/net/conversion/dotx-to-xltx/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: XLTX
otherformats: XLAM ODS TSV XLT FODS XLTX DIF XLTM XLS SXC XLSM XLSB EXCEL XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API เพื่อแปลง DOTX เป็น XLTX" h2="ส่งออก DOTX เป็น XLTX ผ่าน C# โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถรวมคุณลักษณะการแปลง DOTX เป็น XLTX ภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ใดก็ได้ สองขั้นตอนง่ายๆ ประการแรก ด้วยการใช้ [Aspose.Words for .NET](https://products.aspose.com/words/net/) คุณสามารถส่งออก DOTX เป็น HTML หลังจากนั้น การใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API จะช่วยให้คุณแปลง HTML เป็น XLTX ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API เพื่อแปลง DOTX เป็น XLTX" %}}
1. เปิดไฟล์ DOTX โดยใช้คลาส [Document](https://reference.aspose.com/words/net/aspose.words/Document)
2. แปลง DOTX เป็น HTML โดยใช้วิธีการ [Save](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4)
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. บันทึกเอกสารในรูปแบบ XLTX โดยใช้วิธี [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) และตั้งค่า `XLTX' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="โหลดเอกสาร DOTX จากสตรีมผ่าน C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) ยังอนุญาตให้คุณโหลดเอกสาร DOTX ผ่านสตรีม หากต้องการเปิดเอกสารจากสตรีม เพียงส่งออบเจ็กต์สตรีมที่มีเอกสารไปยังตัวสร้าง [Document](https://reference.aspose.com/words/net/aspose.words/Document) ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการเปิดเอกสารจากสตรีม:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-protected-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เพิ่มคุณสมบัติที่กำหนดเองในไฟล์ XLTX ผ่าน C#" %}}
ขณะแปลง DOTX เป็น XLTX [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) ช่วยให้คุณเพิ่มคุณสมบัติที่กำหนดเองในเอกสาร XLTX ได้ ในการเพิ่มคุณสมบัติที่กำหนดเอง คุณสามารถใช้ [เพิ่ม](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection/methods/add/index)เมธอดสำหรับ [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customDocumentpropertycollection) คลาส วิธีการเพิ่มจะเพิ่มคุณสมบัติลงในไฟล์ Excel และส่งคืนข้อมูลอ้างอิงสำหรับคุณสมบัติเอกสารใหม่เป็น [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/Documentproperty) วัตถุ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-protected-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-dif/" name="DOTX ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlsb/" name="DOTX ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-tsv/" name="DOTX ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-fods/" name="DOTX ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlt/" name="DOTX ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-excel/" name="DOTX ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlsx/" name="DOTX ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-ods/" name="DOTX ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-sxc/" name="DOTX ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlam/" name="DOTX ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xltm/" name="DOTX ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xlsm/" name="DOTX ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xls/" name="DOTX ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/dotx-to-xltx/" name="DOTX ถึง XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}