---
title: แปลงรูปแบบ JSON เป็น FLATOPC ผ่าน C++
description: C++ API t0 แยก JSON เป็น FLATOPC โดยไม่ต้องใช้ Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: FLATOPC
otherformats: ODT PCL DOT WORD PS OTT RTF EPUB DOC MOBI CHM DOTX WORDML DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลงรูปแบบ JSON เป็น FLATOPC ผ่าน C++" h2="แยก JSON เป็น FLATOPC ภายในแอปพลิเคชัน C++ โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
ด้วยการใช้ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) คุณสามารถแยก JSON เป็น FLATOPC ภายในแอปพลิเคชัน C++ ของคุณในสองขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) คุณสามารถส่งออก JSON เป็น PDF หลังจากนั้น ด้วยการใช้ [Aspose.Words for C++](https://products.aspose.com/words/cppp/) คุณจะสามารถแปลง PDF เป็น FLATOPC ได้ 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น FLATOPC ใน C++" %}}
1. สร้าง [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. บันทึก JSON เป็น PDF โดยใช้วิธี [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. โหลดเอกสาร PDF โดยใช้ [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class
4. บันทึกเอกสารในรูปแบบ FLATOPC โดยใช้วิธี [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น FLATOPC ใน C++" %}}
ขณะแยกวิเคราะห์ JSON เป็น FLATOPC คุณยังกำหนดขนาดของแถวและคอลัมน์ได้ด้วยการโหลด JSON ด้วยคลาส [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) หากคุณต้องการตั้งค่าความสูงของแถวเท่ากันสำหรับทุกแถวในเวิร์กชีต คุณสามารถทำได้โดยใช้[SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) วิธีการของคอลเล็กชัน [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) ในทำนองเดียวกัน หากต้องการตั้งค่าความกว้างคอลัมน์เท่ากันสำหรับทุกคอลัมน์ในเวิร์กชีต ให้ใช้เมธอด [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) ของคอลเล็กชัน ICElls
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลงรูปแบบ JSON เป็น FLATOPC พร้อมลายน้ำใน C++" %}}
เมื่อใช้ API คุณสามารถแยก JSON เป็น FLATOPC ด้วยลายน้ำได้ ในการเพิ่มลายน้ำให้กับเอกสาร FLATOPC ของคุณ ขั้นแรกให้แปลง JSON เป็น PDF และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PDF ที่สร้างขึ้นใหม่โดยใช้คลาส [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) ตั้งค่าคุณสมบัติที่แตกต่างกันสำหรับลายน้ำข้อความ
เรียกวิธี SetText และส่งข้อความลายน้ำและวัตถุของ TextWatermarkOptions หลังจากเพิ่มลายน้ำแล้ว คุณสามารถบันทึกเอกสารไปที่ FLATOPC
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}