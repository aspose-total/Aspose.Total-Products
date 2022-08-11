---
title: แปลง DOC เป็น XLTM ใน C++
description: C++ API เพื่อแปลง DOC เป็น XLTM โดยไม่ต้องใช้ Microsoft Word หรือ Microsoft Excel
url: /th/cpp/conversion/doc-to-xltm/
family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: XLTM
otherformats: XLS DIF SXC XLSB XLAM XLSX ODS TSV CSV FODS XLTX EXCEL XLT XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อแปลง DOC เป็น XLTM" h2="ส่งออก DOC เป็น XLTM ผ่าน C++ โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถรวมคุณลักษณะการแปลง DOC เป็น XLTM ไว้ในแอปพลิเคชัน C++ ของคุณได้อย่างง่ายดาย ด้วยการใช้ API การจัดการและการแปลงเอกสารที่มีคุณลักษณะหลากหลาย ทรงพลัง และใช้งานง่าย [Aspose.Words for C++](https://products.aspose.com/words/cpp/) คุณสามารถส่งออก DOC เป็น HTML ได้ หลังจากนั้น เมื่อใช้ [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) คุณจะแปลง HTML เป็น XLTM ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง DOC เป็น XLTM" %}}
1. เปิดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) การอ้างอิงคลาส
2. แปลง DOC เป็น HTML โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
3. โหลดเอกสาร HTML โดยใช้ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ XLTM โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="เข้าถึงคุณสมบัติเอกสาร DOC ผ่าน C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) ยังให้คุณเข้าถึงคุณสมบัติของเอกสารของไฟล์ DOC และให้คุณตัดสินใจอย่างมีข้อมูลก่อนขั้นตอนการแปลง ในการเข้าถึงคุณสมบัติของเอกสาร คุณสามารถใช้ [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties) เพื่อรับคุณสมบัติในตัวและ [CustomDocumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties) เพื่อรับคุณสมบัติที่กำหนดเอง ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการระบุคุณสมบัติที่มีอยู่แล้วภายในและแบบกำหนดเองทั้งหมดในเอกสาร
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="บันทึกไฟล์ XLTM เพื่อสตรีมผ่าน C++" %}}
หลังจากแปลง DOC เป็น XLTM แล้ว [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) จะช่วยให้คุณบันทึกเอกสารเพื่อสตรีมได้ ในการบันทึกไฟล์ไปยังสตรีม ให้สร้างวัตถุ MemoryStream หรือ FileStream และบันทึกไฟล์ไปยังวัตถุสตรีมนั้นโดยเรียก [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) วิธีการ [บันทึก](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) ของวัตถุ ระบุรูปแบบไฟล์ที่ต้องการโดยใช้การแจงนับ [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) เมื่อเรียกใช้ [บันทึก](https://reference.aspose.com) วิธีการ
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-xls/" name="DOC ถึง XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-dif/" name="DOC ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-sxc/" name="DOC ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-xlsb/" name="DOC ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-xlam/" name="DOC ถึง XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-xlsx/" name="DOC ถึง XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-ods/" name="DOC ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-tsv/" name="DOC ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-xltm/" name="DOC ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-fods/" name="DOC ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-xltx/" name="DOC ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-excel/" name="DOC ถึง EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-xlt/" name="DOC ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/doc-to-xlsm/" name="DOC ถึง XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}