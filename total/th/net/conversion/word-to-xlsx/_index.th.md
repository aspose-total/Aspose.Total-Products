---
title: .NET API เพื่อแปลง WORD เป็น XLSX
description: C# API เพื่อแปลง WORD เป็น XLSX หรือทางออนไลน์ โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader หรือทางออนไลน์ ทดสอบตัวแปลง CSV เป็น DOC ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด หรือด้วยตัวแปลงออนไลน์ฟรี
url_ignore: /th/net/conversion/word-to-xlsx/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: XLSX
otherformats: SXC XLSX ODS XLSX EXCEL XLAM XLT XLSM XLTX TSV XLTM FODS XLSB XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API เพื่อแปลง WORD เป็น XLSX หรือทางออนไลน์" h2="ส่งออก WORD เป็น XLSX ผ่าน C# โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถรวมคุณลักษณะการแปลง WORD เป็น XLSX ภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ใดก็ได้ สองขั้นตอนง่ายๆ ประการแรก ด้วยการใช้ [Aspose.Words for .NET](https://products.aspose.com/words/net/) คุณสามารถส่งออก WORD เป็น HTML หลังจากนั้น การใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API จะช่วยให้คุณแปลง HTML เป็น XLSX ได้
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API เพื่อแปลง WORD เป็น XLSX" %}}
1. เปิดไฟล์ WORD โดยใช้คลาส [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. แปลง WORD เป็น HTML โดยใช้วิธีการ [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. โหลดเอกสาร HTML โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. บันทึกเอกสารในรูปแบบ XLSX โดยใช้วิธี [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) และตั้งค่า `XLSX' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ WORD เป็น XLSX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=xlsx&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="โหลดเอกสาร WORD จากสตรีมผ่าน C#" %}}
[Aspose.Words for .NET](https://products.aspose.com/words/net/) ยังอนุญาตให้คุณโหลดเอกสาร WORD ผ่านสตรีม หากต้องการเปิดเอกสารจากสตรีม เพียงส่งออบเจ็กต์สตรีมที่มีเอกสารไปยังตัวสร้าง [Document](https://reference.aspose.com/words/net/aspose.words/document) ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการเปิดเอกสารจากสตรีม:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-protected-word-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เพิ่มคุณสมบัติที่กำหนดเองในไฟล์ XLSX ผ่าน C#" %}}
ขณะแปลง WORD เป็น XLSX [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) ช่วยให้คุณเพิ่มคุณสมบัติที่กำหนดเองในเอกสาร XLSX ได้ ในการเพิ่มคุณสมบัติที่กำหนดเอง คุณสามารถใช้ [เพิ่ม](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index)เมธอดสำหรับ [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) คลาส วิธีการเพิ่มจะเพิ่มคุณสมบัติลงในไฟล์ Excel และส่งคืนข้อมูลอ้างอิงสำหรับคุณสมบัติเอกสารใหม่เป็น [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties /documentproperty) วัตถุ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-protected-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-dif/" name="WORD ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-xlsb/" name="WORD ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-tsv/" name="WORD ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-fods/" name="WORD ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-xlt/" name="WORD ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-excel/" name="WORD ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-xlsx/" name="WORD ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-ods/" name="WORD ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-sxc/" name="WORD ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-xlam/" name="WORD ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-xltm/" name="WORD ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-xlsm/" name="WORD ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-xls/" name="WORD ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/word-to-xltx/" name="WORD ถึง XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}