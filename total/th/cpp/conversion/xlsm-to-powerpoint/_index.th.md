---
title: แปลง XLSM เป็น POWERPOINT ด้วย C++
description: แปลง XLSM เป็น POWERPOINT ภายในแอปพลิเคชัน C++
url: /th/cpp/conversion/xlsm-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: PPTX
otherformats: DOC WORD PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง XLSM เป็น POWERPOINT ผ่าน C++" h2="ส่งออก Excel<sup>&reg;</sup> XLSM เป็น POWERPOINT ภายในแอปพลิเคชัน C++ ที่ทำงานได้เต็มรูปแบบ" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="การแปลง XLSM เป็น POWERPOINT บน C++" %}}
1. เปิดไฟล์ XLSM โดยใช้ฟังก์ชันสมาชิกของ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ของ [Factory](https://reference.aspose.com/cells) /cpp/class/aspose.cells.factory) การอ้างอิงคลาส
2. แปลง XLSM เป็น PDF และตั้งค่า SaveFormat เป็น Pdf
3. โหลดไฟล์ PDF ที่แปลงแล้วโดยใช้ [Powerpointument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ POWERPOINT โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) และตั้งค่า Powerpoint เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsm");
// save XLSM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xlsm-to-powerpoint/" name="XLSM ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xlsm-to-word/" name="XLSM ถึง WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xlsm-to-pptx/" name="XLSM ถึง PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xlsm-to-powerpointx/" name="XLSM ถึง POWERPOINTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}