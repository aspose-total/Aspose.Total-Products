---
title: C++ API เพื่อแปลง XPS เป็น TXT
description: แปลง XPS เป็น TXT ผ่าน C++ API โดยไม่ต้องใช้ Microsoft Excel หรือ Adobe Reader
url: /th/cpp/conversion/xps-to-txt/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: TXT
otherformats: ODS XLTM XLSM SXC XLSB FODS MD XLT XLTX TSV DIF XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดงผล XPS เป็น TXT ในแอปพลิเคชัน C++" h2="แปลง XPS เป็น TXT ในแอปพลิเคชัน C++ ดั้งเดิมโดยไม่ต้องใช้ Microsoft<sup>&reg;</sup> Excel หรือ Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
การแปลง XPS เป็น TXT ใน C++ ผ่าน [Aspose.Total for C++](https://products.aspose.com/total/cpp/) ไลบรารีอัตโนมัติของรูปแบบไฟล์เป็นกระบวนการสองขั้นตอนง่ายๆ ในขั้นตอนแรก คุณสามารถส่งออก XPS ไปยัง XLSX ได้โดยใช้ [Aspose.PDF สำหรับ C++](https://products.aspose.com/pdf/cpp/) หลังจากนั้นโดยใช้ [Aspose.Cells for C++]( https://products.aspose.com/cells/cpp/) API การเขียนโปรแกรมสเปรดชีต คุณสามารถแปลง XLSX เป็น TXT 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API เพื่อแปลง XPS เป็น TXT" %}}
1. เปิดไฟล์ XPS โดยใช้ [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. แปลง XPS เป็น XLSX โดยใช้ฟังก์ชันสมาชิก [บันทึก](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. โหลดเอกสาร XLSX โดยใช้ [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) การอ้างอิงคลาส
4. บันทึกเอกสารในรูปแบบ TXT โดยใช้ฟังก์ชันสมาชิก [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Total.Cpp``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/total/cpp)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับหรือตั้งค่าข้อมูลไฟล์ XPS ผ่าน C++" %}}
[Aspose.PDF สำหรับ C++](https://products.aspose.com/pdf/cpp/) ยังช่วยให้คุณได้รับข้อมูลเกี่ยวกับเอกสาร XPS ของคุณและช่วยให้คุณตัดสินใจอย่างมีข้อมูลก่อนกระบวนการแปลงของคุณ ในการรับข้อมูลเฉพาะไฟล์ของไฟล์ XPS ก่อนอื่นคุณต้องเรียกใช้เมธอด [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) ของ [เอกสาร](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) คลาส เมื่อดึงวัตถุ DocumentInfo แล้ว คุณจะได้รับค่าของคุณสมบัติแต่ละรายการ นอกจากนี้ คุณยังสามารถตั้งค่าคุณสมบัติโดยใช้วิธีการที่เกี่ยวข้องของคลาส DocumentInfo
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="บันทึกรูปแบบไฟล์ TXT เพื่อสตรีมผ่าน C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) อนุญาตให้บันทึกรูปแบบไฟล์ TXT เพื่อสตรีม ในการบันทึกไฟล์ไปยังสตรีม ให้สร้างวัตถุ MemoryStream หรือ FileStream และบันทึกไฟล์ไปยังวัตถุสตรีมนั้นโดยเรียก [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) วิธีการ [บันทึก](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) ของวัตถุ ระบุรูปแบบไฟล์ที่ต้องการโดยใช้การแจงนับ [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) เมื่อเรียกใช้เมธอด Save
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-txt-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-ods/" name="XPS ถึง ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-xltm/" name="XPS ถึง XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-xlsm/" name="XPS ถึง XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-sxc/" name="XPS ถึง SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-xlsb/" name="XPS ถึง XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-fods/" name="XPS ถึง FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-md/" name="XPS ถึง MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-xlt/" name="XPS ถึง XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-xltx/" name="XPS ถึง XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-tsv/" name="XPS ถึง TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-dif/" name="XPS ถึง DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/cpp/conversion/xps-to-xlam/" name="XPS ถึง XLAM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}