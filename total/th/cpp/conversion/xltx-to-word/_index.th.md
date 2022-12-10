---
title: แปลง XLTX เป็น WORD ด้วย C++
description: แปลง XLTX เป็น WORD ภายในแอปพลิเคชัน C++

family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: DOC
otherformats: DOCX POWERPOINT PPTX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง XLTX เป็น WORD ผ่าน C++" h2="ส่งออก Excel<sup>&reg;</sup> XLTX เป็น WORD ภายในแอปพลิเคชัน C++ ที่ทำงานได้เต็มรูปแบบ" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="การแปลง XLTX เป็น WORD บน C++" %}}
1. เปิดไฟล์ XLTX โดยใช้ฟังก์ชันสมาชิกของ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ของ [Factory](https://reference.aspose.com/cells) /cpp/class/aspose.cells.factory) การอ้างอิงคลาส
2. แปลง XLTX เป็น PDF และตั้งค่า SaveFormat เป็น Pdf
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้ [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ WORD โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) และตั้งค่า Word เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");
// save XLTX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xltx-to-wordx/" name="XLTX ถึง WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xltx-to-powerpoint/" name="XLTX ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xltx-to-pptx/" name="XLTX ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xltx-to-word/" name="XLTX ถึง WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}