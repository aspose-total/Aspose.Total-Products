---
title: แปลง PPTM เป็น XLTX โดยใช้ Python
description: การแปลง PPTM เป็น XLTX ในแอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPTM
outformat: XLTX
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง PPTM เป็น XLTX ผ่าน Python" h2="การแปลง PPTM เป็น XLTX ในแอปพลิเคชัน Python โดยไม่ต้องติดตั้ง Microsoft PowerPoint<sup>&reg;</sup> หรือ Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ที่พยายามเพิ่มคุณสมบัติการแปลง PPTM เป็น XLTX ภายในแอปพลิเคชัน [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่เกี่ยวข้องกับรูปแบบต่างๆ รวมถึงไฟล์ PPTM และ XLTX

ส่วนใหญ่อยู่ในสองขั้นตอน ขั้นแรกให้ใช้ [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API เพื่อแปลงไฟล์ PPTM เป็น HTML หลังจากนั้นโดยใช้ Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) ให้บันทึก HTML ที่สร้างขึ้นเป็นรูปแบบ Microsoft Excel ที่ต้องการ 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง PPTM เป็น XLTX ใน Python" %}}
- **ขั้นตอนที่ 1** ใช้อินสแตนซ์คลาส [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) เพื่อเปิดไฟล์ PPTM ต้นทาง 
- บันทึกไฟล์ PPTM เป็น HTML โดยใช้วิธี [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) โดยระบุชื่อไฟล์และเส้นทางไดเร็กทอรีที่ต้องการ
-  **ขั้นตอนที่ 2** โหลดไฟล์ HTML ด้วยอินสแตนซ์ของคลาส Workbook
-  เรียกใช้เมธอด "save" ขณะระบุพาธไฟล์ XLTX เอาต์พุต ดังนั้นไฟล์ PPTM ของคุณจึงถูกแปลงเป็น XLTX ตามเส้นทางที่ระบุ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลง PPTM เป็น XLTX จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) และ [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  หรือใช้คำสั่ง pip ต่อไปนี้ ``` pip install aspose.slides``` และ ```pip install aspose-cells-python```
-  นอกจากนี้ ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) และ [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="บันทึก PPTM เป็น HTML ใน Python - ขั้นตอนที่ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="บันทึก HTML เป็น XLTX ใน Python - ขั้นตอนที่ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}