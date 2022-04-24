---
title: .NET API เพื่อแปลง DOC เป็น TSV
description: C# API เพื่อแปลง DOC เป็น TSV โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url: /th/net/conversion/doc-to-tsv/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: TSV
otherformats: ODS FODS XLSB XLTX XLSM EXCEL TSV XLSX XLTM SXC XLAM XLT DIF XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API เพื่อแปลง DOC เป็น TSV" h2="ส่งออก DOC เป็น TSV ผ่าน C# โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถรวมคุณลักษณะการแปลง DOC เป็น TSV ภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ใดก็ได้ สองขั้นตอนง่ายๆ ประการแรก ด้วยการใช้ [Aspose.Words for .NET](https://products.aspose.com/words/net/) คุณสามารถส่งออก DOC เป็น HTML หลังจากนั้น การใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API จะช่วยให้คุณแปลง HTML เป็น TSV ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API เพื่อแปลง DOC เป็น TSV" %}}
1. เปิดไฟล์ DOC โดยใช้คลาส [Document](https://apireference.aspose.com/words/net/aspose.words/document)
2. แปลง DOC เป็น HTML โดยใช้วิธีการ [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. บันทึกเอกสารในรูปแบบ TSV โดยใช้วิธี [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) และตั้งค่า `TSV' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="โหลดเอกสาร DOC จากสตรีมผ่าน C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) ยังอนุญาตให้คุณโหลดเอกสาร DOC ผ่านสตรีม หากต้องการเปิดเอกสารจากสตรีม เพียงส่งออบเจ็กต์สตรีมที่มีเอกสารไปยังตัวสร้าง [Document](https://apireference.aspose.com/words/net/aspose.words/document) ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการเปิดเอกสารจากสตรีม:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="เพิ่มคุณสมบัติที่กำหนดเองในไฟล์ TSV ผ่าน C#" %}}
ขณะแปลง DOC เป็น TSV [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) ช่วยให้คุณเพิ่มคุณสมบัติที่กำหนดเองในเอกสาร TSV ได้ ในการเพิ่มคุณสมบัติที่กำหนดเอง คุณสามารถใช้ [เพิ่ม](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index)เมธอดสำหรับ [CustomDocumentPropertyCollection]( https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) คลาส วิธีการเพิ่มจะเพิ่มคุณสมบัติลงในไฟล์ Excel และส่งคืนข้อมูลอ้างอิงสำหรับคุณสมบัติเอกสารใหม่เป็น [Aspose.Cells.Properties.DocumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties /documentproperty) วัตถุ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-dif/" name="DOC ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-xlsb/" name="DOC ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-tsv/" name="DOC ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-fods/" name="DOC ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-xlt/" name="DOC ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-excel/" name="DOC ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-xlsx/" name="DOC ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-ods/" name="DOC ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-sxc/" name="DOC ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-xlam/" name="DOC ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-xltm/" name="DOC ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-xlsm/" name="DOC ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-xls/" name="DOC ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/doc-to-xltx/" name="DOC ถึง XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}