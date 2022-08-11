---
title: C++ API เพื่อแปลง TEX เป็น XLAM
description: แปลง TEX เป็น XLAM ผ่าน C++ API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url: /th/cpp/conversion/tex-to-xlam/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: XLAM
otherformats: TXT CSV XLTM DIF ODS EXCEL SXC FODS XLSM XLT MD TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดงผล TEX เป็น XLAM ในแอปพลิเคชัน C++" h2="แปลง TEX เป็น XLAM ในแอปพลิเคชัน C++ ดั้งเดิมโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
การแปลง TEX เป็น XLAM ใน C++ ผ่าน [Aspose.Total for C++](https://products.aspose.com/total/cpp/) ไลบรารีอัตโนมัติของรูปแบบไฟล์เป็นกระบวนการสองขั้นตอนง่ายๆ ในขั้นตอนแรก คุณสามารถส่งออก TEX ไปยัง XLSX ได้โดยใช้ [Aspose.PDF สำหรับ C++](https://products.aspose.com/pdf/cpp/) หลังจากนั้นโดยใช้ [Aspose.Cells for C++]( https://products.aspose.com/cells/cpp/) API การเขียนโปรแกรมสเปรดชีต คุณสามารถแปลง XLSX เป็น XLAM 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง TEX เป็น XLAM" %}}
1. เปิดไฟล์ TEX โดยใช้ [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. แปลง TEX เป็น XLSX โดยใช้ฟังก์ชันสมาชิก [บันทึก](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. โหลดเอกสาร XLSX โดยใช้ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ XLAM โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับหรือตั้งค่าข้อมูลไฟล์ TEX ผ่าน C++" %}}
[Aspose.PDF สำหรับ C++](https://products.aspose.com/pdf/cpp/) ยังช่วยให้คุณได้รับข้อมูลเกี่ยวกับเอกสาร TEX ของคุณและช่วยให้คุณตัดสินใจอย่างมีข้อมูลก่อนกระบวนการแปลงของคุณ ในการรับข้อมูลเฉพาะไฟล์ของไฟล์ TEX ก่อนอื่นคุณต้องเรียกใช้เมธอด [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) ของ [เอกสาร](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) คลาส เมื่อดึงวัตถุ DocumentInfo แล้ว คุณจะได้รับค่าของคุณสมบัติแต่ละรายการ นอกจากนี้ คุณยังสามารถตั้งค่าคุณสมบัติโดยใช้วิธีการที่เกี่ยวข้องของคลาส DocumentInfo
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="บันทึกรูปแบบไฟล์ XLAM เพื่อสตรีมผ่าน C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) อนุญาตให้บันทึกรูปแบบไฟล์ XLAM เพื่อสตรีม ในการบันทึกไฟล์ไปยังสตรีม ให้สร้างวัตถุ MemoryStream หรือ FileStream และบันทึกไฟล์ไปยังวัตถุสตรีมนั้นโดยเรียก [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) วิธีการ [บันทึก](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) ของวัตถุ ระบุรูปแบบไฟล์ที่ต้องการโดยใช้การแจงนับ [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) เมื่อเรียกใช้เมธอด Save
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlam-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-txt/" name="TEX ถึง TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-xlam/" name="TEX ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-xltm/" name="TEX ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-dif/" name="TEX ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-ods/" name="TEX ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-excel/" name="TEX ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-sxc/" name="TEX ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-fods/" name="TEX ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-xlsm/" name="TEX ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-xlt/" name="TEX ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-md/" name="TEX ถึง MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/tex-to-tsv/" name="TEX ถึง TSV" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}