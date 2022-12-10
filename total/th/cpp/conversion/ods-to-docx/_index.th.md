---
title: แปลง ODS เป็น DOCX ด้วย C++
description: แปลง ODS เป็น DOCX ภายในแอปพลิเคชัน C++

family: total
platformtag: cpp
feature: conversion
informat: ODS
outformat: DOCX
otherformats: PPTX POWERPOINT DOC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง ODS เป็น DOCX ผ่าน C++" h2="ส่งออก Excel<sup>&reg;</sup> ODS เป็น DOCX ภายในแอปพลิเคชัน C++ ที่ทำงานได้เต็มรูปแบบ" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="การแปลง ODS เป็น DOCX บน C++" %}}
1. เปิดไฟล์ ODS โดยใช้ฟังก์ชันสมาชิกของ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ของ [Factory](https://reference.aspose.com/cells) /cpp/class/aspose.cells.factory) การอ้างอิงคลาส
2. แปลง ODS เป็น PDF และตั้งค่า SaveFormat เป็น Pdf
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้ [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ DOCX โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) และตั้งค่า Docx เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");
// save ODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto docx = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/ods-to-pptx/" name="ODS ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/ods-to-powerpoint/" name="ODS ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/ods-to-docx/" name="ODS ถึง DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/ods-to-word/" name="ODS ถึง WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}