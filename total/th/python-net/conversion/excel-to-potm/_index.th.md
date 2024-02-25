---
title: แปลง EXCEL เป็น POTM โดยใช้ Python
description: การแปลง EXCEL เป็น POTM ในแอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: EXCEL
outformat: POTM
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง EXCEL เป็น POTM ผ่าน Python" h2="การแปลง EXCEL เป็น POTM ในแอปพลิเคชัน Python โดยไม่ต้องติดตั้ง Microsoft Excel<sup>&reg;</sup> หรือ PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ที่พยายามเพิ่มคุณสมบัติการแปลง EXCEL เป็น POTM ภายในแอปพลิเคชัน, [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่เกี่ยวข้องกับรูปแบบต่างๆ รวมถึงไฟล์ EXCEL และ POTM.

ส่วนใหญ่อยู่ในสองขั้นตอน. ขั้นแรกให้ใช้ [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API เพื่อแปลงไฟล์ EXCEL เป็น PDF. หลังจากนั้นโดยใช้ PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) ให้บันทึก PDF ที่สร้างขึ้นเป็นรูปแบบ Microsoft PowerPoint ที่ต้องการ. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง EXCEL เป็น POTM ใน Python" %}}
- **ขั้นตอนที่ 1** ใช้อินสแตนซ์คลาส Workbook เพื่อเปิดไฟล์ EXCEL ต้นทาง 
- บันทึกไฟล์ EXCEL เป็น PDF โดยใช้วิธี save โดยระบุชื่อไฟล์และเส้นทางไดเร็กทอรีที่ต้องการ
-  **ขั้นตอนที่ 2** โหลดไฟล์ PDF โดยใช้คลาส [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  เรียกใช้เมธอด [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) ขณะระบุพาธไฟล์ POTM เอาต์พุต. ดังนั้นไฟล์ EXCEL ของคุณจึงถูกแปลงเป็น POTM ตามเส้นทางที่ระบุ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลง EXCEL เป็น POTM จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) และ [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose-cells-python``` และ ```pip install aspose.slides```
-  นอกจากนี้ ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) และ [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="บันทึก EXCEL เป็น PDF ใน Python - ขั้นตอนที่ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="บันทึก PDF เป็น POTM ใน Python - ขั้นตอนที่ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}