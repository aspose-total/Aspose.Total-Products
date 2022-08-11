---
title: แปลง XLSB เป็น PPTX ด้วย C++
description: แปลง XLSB เป็น PPTX ภายในแอปพลิเคชัน C++
url: /th/cpp/conversion/xlsb-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLSB
outformat: PPTX
otherformats: DOCX WORD POWERPOINT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง XLSB เป็น PPTX ผ่าน C++" h2="ส่งออก Excel&reg; XLSB เป็น PPTX ภายในแอปพลิเคชัน C++ ที่ทำงานได้เต็มรูปแบบ" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="การแปลง XLSB เป็น PPTX บน C++" %}}
1. เปิดไฟล์ XLSB โดยใช้ฟังก์ชันสมาชิกของ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ของ [Factory](https://reference.aspose.com/cells) /cpp/class/aspose.cells.factory) การอ้างอิงคลาส
2. แปลง XLSB เป็น PDF และตั้งค่า SaveFormat เป็น Pdf
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้ [Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ PPTX โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) และตั้งค่า Pptx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSB file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsb");
// save XLSB as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xlsb-to-pptxx/" name="XLSB ถึง PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xlsb-to-word/" name="XLSB ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xlsb-to-powerpoint/" name="XLSB ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xlsb-to-pptx/" name="XLSB ถึง PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}