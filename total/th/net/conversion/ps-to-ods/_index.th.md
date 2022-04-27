---
title: แปลง PS เป็น ODS ผ่าน C# API
description: C# API เพื่อแปลงไฟล์ PS เป็น ODS โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url: /th/net/conversion/ps-to-ods/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: ODS
otherformats: XLTM FODS XLSM EXCEL XLT XLAM MD TXT TSV XLSB XLTX DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API เพื่อแสดงผล PS เป็น ODS" h2="ส่งออกไฟล์ PS เป็น ODS ผ่าน C# โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
การใช้ [Aspose.Total for .NET](https://products.aspose.com/total/net/) คุณสามารถแปลงไฟล์ PS เป็น ODS ได้อย่างง่ายดายภายในแอปพลิเคชัน .NET, C#, ASP.NET และ VB.NET ประการแรก ด้วยการใช้ [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) คุณสามารถส่งออก PS ไปยัง XLSX ได้ หลังจากนั้น คุณสามารถใช้ [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API เพื่อแปลง XLSX เป็น ODS
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API เพื่อแปลง PS เป็น ODS" %}}
1. เปิดไฟล์ PS โดยใช้คลาส [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. แปลง PS เป็น XLSX โดยใช้วิธีการ [บันทึก](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. โหลดเอกสาร XLSX โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. บันทึกเอกสารในรูปแบบ ODS โดยใช้เมธอด [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) และตั้งค่า `Ods' เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="แปลง PS ที่ได้รับการป้องกันเป็น ODS ผ่าน C #" %}}
หากเอกสาร PS ของคุณมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็น ODS ได้หากไม่มีรหัสผ่าน เมื่อใช้ API คุณสามารถเปิดเอกสารที่มีการป้องกันโดยใช้รหัสผ่านที่ถูกต้องและแปลงหลังจากนั้น ในการเปิดไฟล์ที่เข้ารหัส คุณสามารถเริ่มต้นอินสแตนซ์ใหม่ของคลาส [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) และส่งชื่อไฟล์และรหัสผ่านเป็นอาร์กิวเมนต์ได้  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}C#

{{% blocks/products/pf/feature-page-section  h2="แปลงไฟล์ PS เป็น ODS พร้อมลายน้ำผ่าน C #" %}}
ในขณะที่แปลงไฟล์ PS เป็น ODS คุณยังสามารถเพิ่มลายน้ำให้กับรูปแบบไฟล์ ODS เอาต์พุตของคุณ ในการเพิ่มลายน้ำ คุณสามารถสร้างวัตถุสมุดงานใหม่และเปิดเอกสาร XLSX ที่แปลงแล้ว เลือกแผ่นงานผ่านดัชนี สร้างรูปร่าง และใช้ฟังก์ชัน AddTextEffect หลังจากนั้น คุณสามารถบันทึกเอกสาร XLSX ของคุณเป็น ODS ด้วยลายน้ำ 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-sxc/" name="PS ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-xltx/" name="PS ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-md/" name="PS ถึง MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-tsv/" name="PS ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-txt/" name="PS ถึง TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-ods/" name="PS ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-xlt/" name="PS ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-xlsm/" name="PS ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-xlam/" name="PS ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-xltm/" name="PS ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-dif/" name="PS ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/net/conversion/ps-to-xlsb/" name="PS ถึง XLSB" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}