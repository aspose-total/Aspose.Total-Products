---
title: แปลงรูปแบบ DOC เป็นรูปแบบ JSON ใน C++
description: ส่งออก DOC เป็น JSON ใน C++ โดยไม่ต้องใช้ Microsoft Excel หรือ Word

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง DOC เป็นรูปแบบ JSON ผ่าน C++" h2="ส่งออก DOC เป็น JSON ผ่าน C++ โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word หรือ Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) คุณสามารถแปลง DOC เป็นรูปแบบ JSON ภายในแอปพลิเคชัน C++ ของคุณได้ ประการแรก โดยใช้ [Aspose.Words for C++](https://products.aspose.com/words/cpp/) คุณสามารถส่งออก DOC เป็น HTML หลังจากนั้น เมื่อใช้ [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) คุณจะแปลงรูปแบบ HTML เป็นรูปแบบ JSON ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลง DOC เป็นรูปแบบ JSON ผ่าน C++" %}}
1. เปิดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) การอ้างอิงคลาส
2. แปลง DOC เป็น HTML โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
3. โหลดเอกสาร HTML โดยใช้ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ JSON โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="แปลง DOC ที่ได้รับการป้องกันเป็นรูปแบบ JSON ผ่าน C++" %}}
คุณยังสามารถเปิดเอกสารที่ป้องกันด้วยรหัสผ่านโดยใช้ API ได้อีกด้วย หากเอกสาร DOC ที่คุณป้อนมีการป้องกันด้วยรหัสผ่าน คุณจะไม่สามารถแปลงเป็นรูปแบบ JSON ได้โดยไม่ต้องใช้รหัสผ่าน เมื่อต้องการทำเช่นนี้ ใช้คอนสตรัคโอเวอร์โหลดพิเศษ ซึ่งยอมรับอ็อบเจ็กต์ LoadOptions วัตถุนี้มีคุณสมบัติ Password ซึ่งระบุสตริงรหัสผ่าน
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}