---
title: แปลง SVG เป็น EXCEL ผ่าน C# API
description: C# API เพื่อแปลงไฟล์ SVG เป็น EXCEL โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url_ignore: /th/net/conversion/svg-to-excel/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: EXCEL
otherformats: XLAM MD DIF XLSB XLT XLTX TXT FODS TSV SXC XLTM EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API เพื่อแสดงผล SVG เป็น EXCEL" h2="ส่งออกไฟล์ SVG เป็น EXCEL ผ่าน C# โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
การใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถแปลงไฟล์ SVG เป็น EXCEL ได้อย่างง่ายดายภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ประการแรก ด้วยการใช้ [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณสามารถส่งออก SVG ไปยัง XLSX ได้ หลังจากนั้น คุณสามารถใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API เพื่อแปลง XLSX เป็น EXCEL
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API เพื่อแปลง SVG เป็น EXCEL" %}}
1. เปิดไฟล์ SVG โดยใช้คลาส [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. แปลง SVG เป็น XLSX โดยใช้วิธีการ [บันทึก](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. บันทึกเอกสารในรูปแบบ EXCEL โดยใช้เมธอด [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) และตั้งค่า `Excel' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="แปลง SVG ที่ได้รับการป้องกันเป็น EXCEL ผ่าน C#" %}}
หากเอกสาร SVG ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น EXCEL ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของคลาส [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) และส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์ได้  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}C#

{{% blocks/products/pf/feature-page-section  h2="แปลงไฟล์ SVG เป็น EXCEL พร้อมลายน้ำผ่าน C#" %}}
ในขณะที่แปลงไฟล์ SVG เป็น EXCEL คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ EXCEL เอาต์พุตของคุณ ในการเพิ่มลายน้ำ คุณสามารถสร้างวัตถุสมุดงานใหม่และเปิดเอกสาร XLSX ที่แปลงแล้ว เลือกแผ่นงานผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน AddTextEffect หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น EXCEL ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}