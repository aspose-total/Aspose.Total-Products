---
title: แปลง XLS เป็น DOCX ด้วย .NET หรือด้วยตัวแปลงออนไลน์ฟรี
description: แปลง XLS เป็น DOCX บน .NET Framework, .NET Core, Mono หรือ Xamarin Platforms หรือทางออนไลน์ ทดสอบตัวแปลง CSV เป็น DOC ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด

family: total
platformtag: net
feature: conversion
informat: XLS
outformat: DOCX
otherformats: DOC POWERPOINT PPTX WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="แปลง XLS เป็น DOCX ผ่าน C# หรือแอพออนไลน์" h2="ส่งออก Excel&reg; XLS เป็น DOCX บน .NET Framework, .NET Core, Mono หรือ Xamarin Platforms">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="การแปลง XLS เป็น DOCX บน .NET" %}}
1. เปิดไฟล์ XLS โดยใช้คลาส [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. แปลง XLS เป็น PDF และตั้งค่า SaveFormat เป็น Auto
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้คลาส [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. บันทึกเอกสารในรูปแบบ DOCX โดยใช้วิธี [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) และตั้งค่า Docx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget install Aspose.Total``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Code สำหรับการแปลง XLS เป็น DOCX" gistPath="" %}}
```cs
// load the XLS file using Workbook class
var book = new Aspose.Cells.Workbook("input.xls");
// save XLS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ XLS เป็น DOCX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xls" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}