---
title: C++ API เพื่อแปลง MHTML เป็น XLTX
description: แปลง MHTML เป็น XLTX ผ่าน C++ API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: XLTX
otherformats: XLAM EXCEL SXC TSV TXT XLTM XLSB FODS ODS XLSM XLT CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดงผล MHTML เป็น XLTX ในแอปพลิเคชัน C++" h2="แปลง MHTML เป็น XLTX ในแอปพลิเคชัน C++ ดั้งเดิมโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
การแปลง MHTML เป็น XLTX ใน C++ ผ่าน [Aspose.Total for C++](https://products.aspose.com/total/cpp/) ไลบรารีอัตโนมัติของรูปแบบไฟล์เป็นกระบวนการสองขั้นตอนง่ายๆ ในขั้นตอนแรก คุณสามารถส่งออก MHTML ไปยัง XLSX ได้โดยใช้ [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) หลังจากนั้นโดยใช้ [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API การเขียนโปรแกรมสเปรดชีต คุณสามารถแปลง XLSX เป็น XLTX 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง MHTML เป็น XLTX" %}}
1. เปิดไฟล์ MHTML โดยใช้ [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. แปลง MHTML เป็น XLSX โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. โหลดเอกสาร XLSX โดยใช้ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ XLTX โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับหรือตั้งค่าข้อมูลไฟล์ MHTML ผ่าน C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) ยังช่วยให้คุณได้รับข้อมูลเกี่ยวกับเอกสาร MHTML ของคุณและช่วยให้คุณตัดสินใจอย่างมีข้อมูลก่อนกระบวนการแปลงของคุณ ในการรับข้อมูลเฉพาะไฟล์ของไฟล์ MHTML ก่อนอื่นคุณต้องเรียกใช้เมธอด [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) ของ [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) คลาส เมื่อดึงวัตถุ DocumentInfo แล้ว คุณจะได้รับค่าของคุณสมบัติแต่ละรายการ นอกจากนี้ คุณยังสามารถตั้งค่าคุณสมบัติโดยใช้วิธีการที่เกี่ยวข้องของคลาส DocumentInfo
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="บันทึกรูปแบบไฟล์ XLTX เพื่อสตรีมผ่าน C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) อนุญาตให้บันทึกรูปแบบไฟล์ XLTX เพื่อสตรีม ในการบันทึกไฟล์ไปยังสตรีม ให้สร้างวัตถุ MemoryStream หรือ FileStream และบันทึกไฟล์ไปยังวัตถุสตรีมนั้นโดยเรียก [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) วิธีการ [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) ของวัตถุ ระบุรูปแบบไฟล์ที่ต้องการโดยใช้การแจงนับ [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) เมื่อเรียกใช้เมธอด Save
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xltx-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-xlam/" name="MHTML ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-excel/" name="MHTML ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-sxc/" name="MHTML ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-tsv/" name="MHTML ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-txt/" name="MHTML ถึง TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-xltm/" name="MHTML ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-xlsb/" name="MHTML ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-fods/" name="MHTML ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-ods/" name="MHTML ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-xlsm/" name="MHTML ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-xlt/" name="MHTML ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/mhtml-to-xltx/" name="MHTML ถึง XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}