---
title: แปลง DOTX เป็น XLTM ใน C++ หรือด้วยตัวแปลงออนไลน์ฟรี
description: C++ API เพื่อแปลง DOTX เป็น XLTM หรือแอพออนไลน์ โดยไม่ต้องใช้ Microsoft Word หรือ Microsoft Excel หรือทางออนไลน์ ทดสอบตัวแปลง POT เป็น CSV ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: XLTM
otherformats: ODS XLS EXCEL XLSX CSV XLT TSV DIF XLSB FODS XLTX XLSM SXC XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API เพื่อแปลง DOTX เป็น XLTM หรือแอพออนไลน์" h2="ส่งออก DOTX เป็น XLTM ผ่าน C++ โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถรวมคุณลักษณะการแปลง DOTX เป็น XLTM ไว้ในแอปพลิเคชัน C++ ของคุณได้อย่างง่ายดาย ด้วยการใช้ API การจัดการและการแปลงเอกสารที่มีคุณลักษณะหลากหลาย ทรงพลัง และใช้งานง่าย [Aspose.Words for C++](https://products.aspose.com/words/cpp/) คุณสามารถส่งออก DOTX เป็น HTML ได้ หลังจากนั้น เมื่อใช้ [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) คุณจะแปลง HTML เป็น XLTM ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง DOTX เป็น XLTM หรือแอพออนไลน์" %}}
1. เปิดไฟล์ DOTX โดยใช้ [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument) การอ้างอิงคลาส
2. แปลง DOTX เป็น HTML โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_string_saveformat)
3. โหลดเอกสาร HTML โดยใช้ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ XLTM โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="เข้าถึงคุณสมบัติเอกสาร DOTX ผ่าน C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) ยังให้คุณเข้าถึงคุณสมบัติของเอกสารของไฟล์ DOTX และให้คุณตัดสินใจอย่างมีข้อมูลก่อนขั้นตอนการแปลง ในการเข้าถึงคุณสมบัติของเอกสาร คุณสามารถใช้ [BuiltInDotxumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_dotxument_properties) เพื่อรับคุณสมบัติในตัวและ [CustomDotxumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_dotxument_properties) เพื่อรับคุณสมบัติที่กำหนดเอง ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการระบุคุณสมบัติที่มีอยู่แล้วภายในและแบบกำหนดเองทั้งหมดในเอกสาร
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-dotxument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="บันทึกไฟล์ XLTM เพื่อสตรีมผ่าน C++" %}}
หลังจากแปลง DOTX เป็น XLTM แล้ว [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) จะช่วยให้คุณบันทึกเอกสารเพื่อสตรีมได้ ในการบันทึกไฟล์ไปยังสตรีม ให้สร้างวัตถุ MemoryStream หรือ FileStream และบันทึกไฟล์ไปยังวัตถุสตรีมนั้นโดยเรียก [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) วิธีการ [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) ของวัตถุ ระบุรูปแบบไฟล์ที่ต้องการโดยใช้การแจงนับ [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) เมื่อเรียกใช้ [Save](https://reference.aspose.com) วิธีการ
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}