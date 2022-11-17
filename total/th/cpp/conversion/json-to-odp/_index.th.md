---
title: แปลงรูปแบบ JSON เป็น ODP ผ่าน C++
description: แยก JSON เป็น ODP ใน C++ โดยไม่ต้องใช้ Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: ODP
otherformats: POT PPTM PPSM PPSX POWERPOINT PPS POTX POTM PPT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลงรูปแบบ JSON เป็น ODP ผ่าน C++" h2="C++ API เพื่อแยก JSON เป็น ODP โดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง JSON เป็น ODP ภายในแอปพลิเคชัน C++ ใดก็ได้ในสองขั้นตอนง่ายๆ ประการแรก โดยใช้ [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) คุณสามารถแยก JSON เป็น PPTX หลังจากนั้น ด้วยการใช้ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) คุณจะสามารถแปลง PPTX เป็น ODP ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลงรูปแบบ JSON เป็น ODP ผ่าน C++" %}}
1. สร้าง [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ใหม่และอ่านข้อมูล JSON ที่ถูกต้องจากไฟล์
2. บันทึก JSON เป็น PPTX โดยใช้วิธี [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. โหลดเอกสาร PPTX โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class
4. บันทึกเอกสารในรูปแบบ ODP โดยใช้วิธี [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="ตั้งค่าเค้าโครงและแปลงรูปแบบ JSON เป็น ODP ผ่าน C++" %}}
ขณะแยกวิเคราะห์ JSON เป็น ODP คุณยังกำหนดขนาดของแถวและคอลัมน์ได้ด้วยการโหลด JSON ด้วยคลาส [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) หากคุณต้องการตั้งค่าความสูงของแถวเท่ากันสำหรับทุกแถวในเวิร์กชีต คุณสามารถทำได้โดยใช้[SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) วิธีการของคอลเล็กชัน [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) ในทำนองเดียวกัน หากต้องการตั้งค่าความกว้างคอลัมน์เท่ากันสำหรับทุกคอลัมน์ในเวิร์กชีต ให้ใช้เมธอด [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) ของคอลเล็กชัน ICElls
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แปลงรูปแบบ JSON เป็น ODP พร้อมลายน้ำใน C++" %}}
เมื่อใช้ API คุณยังสามารถแปลง JSON เป็น ODP ด้วยลายน้ำ ในการเพิ่มลายน้ำให้กับเอกสาร ODP ของคุณ ขั้นแรกให้แยก JSON เป็น PPTX และเพิ่มลายน้ำลงไป ในการเพิ่มลายน้ำ ให้โหลดไฟล์ PPTX ที่สร้างขึ้นใหม่โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) รับสไลด์แรก เพิ่ม รูปร่างอัตโนมัติของประเภทสี่เหลี่ยมผืนผ้า, เพิ่ม TextFrame ให้กับสี่เหลี่ยมผืนผ้า, สร้างวัตถุย่อหน้าสำหรับกรอบข้อความ, สร้างวัตถุส่วนสำหรับย่อหน้า, เพิ่มลายน้ำโดยใช้ set_Text() และสามารถบันทึกเอกสารไปยัง ODP
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/json-to-pot/" name="JSON ถึง POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/json-to-pptm/" name="JSON ถึง PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/json-to-ppsm/" name="JSON ถึง PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/json-to-ppsx/" name="JSON ถึง PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/json-to-powerpoint/" name="JSON ถึง POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/json-to-pps/" name="JSON ถึง PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/json-to-potx/" name="JSON ถึง POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/json-to-potm/" name="JSON ถึง POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/json-to-ppt/" name="JSON ถึง PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/json-to-otp/" name="JSON ถึง OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}