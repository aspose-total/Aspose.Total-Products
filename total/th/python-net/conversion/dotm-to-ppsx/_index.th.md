---
title: แปลง DOTM เป็น PPSX ใน Python
description: การแปลง DOTM เป็น PPSX ในแอปพลิเคชัน Python ของคุณโดยไม่ต้องใช้ Microsoft Word หรือ PowerPoint 
url: /th/python-net/conversion/dotm-to-ppsx/
family: total
platformtag: Python
feature: conversion
informat: DOTM
outformat: PPSX
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง DOTM เป็น PPSX โดยใช้ Python" h2="การแปลง DOTM เป็น PPSX ในแอปพลิเคชัน Python ของคุณโดยไม่ต้องติดตั้ง Microsoft Word<sup>&reg;</sup> หรือ PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ใครกำลังพยายามเพิ่มคุณสมบัติการแปลง DOTM เป็น PPSX ภายในแอปพลิเคชัน ? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่จัดการรูปแบบต่างๆ  

ส่วนใหญ่อยู่ในสองขั้นตอน ขั้นแรก ใช้ [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API เพื่อแปลงไฟล์ DOTM เป็น PDF หลังจากนั้นโดยใช้ PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) ให้บันทึก PDF ที่สร้างลงในการนำเสนอในรูปแบบ PPSX 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง DOTM เป็น PPSX ใน Python" %}}
- **ขั้นตอนที่ 1** เปิดไฟล์ DOTM ต้นทางโดยใช้คลาส [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- บันทึกไฟล์ DOTM เป็น PDF โดยใช้วิธีการ [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) โดยระบุชื่อไฟล์และเส้นทางไดเรกทอรีที่ต้องการ
-  **ขั้นตอนที่ 2** โหลดไฟล์ PDF ด้วยอินสแตนซ์ของคลาส [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  เรียกใช้เมธอด `บันทึก' ขณะที่ระบุพาธไฟล์เอาต์พุต & SaveFormat.PPSX เป็นพารามิเตอร์ ไฟล์ DOTM ของคุณจะถูกแปลงเป็น PPSX ตามเส้นทางที่ระบุ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลง DOTM เป็น PPSX จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) และ [Aspose.Words](https://pypi.org/project/aspose-words/)) หรือ
- ใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.slides``` และ ```pip install aspose.words``` 
- ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) และ [Words](https://docs.aspose.com/words/python-net/system-requirements/)) และสำหรับ Linux ให้ตรวจสอบข้อกำหนดเพิ่มเติมสำหรับ gcc และ libpython และทำตามคำแนะนำทีละขั้นตอน [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="บันทึก DOTM เป็น PDF ใน Python - ขั้นตอนที่ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="บันทึก PDF เป็น PPSX ใน Python - ขั้นตอนที่ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-powerpoint/" name="DOTM ถึง POWERPOINT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-ppsx/" name="DOTM ถึง PPSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-pptx/" name="DOTM ถึง PPTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-ppt/" name="DOTM ถึง PPT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-pot/" name="DOTM ถึง POT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-potx/" name="DOTM ถึง POTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-potm/" name="DOTM ถึง POTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-pptm/" name="DOTM ถึง PPTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-ppsm/" name="DOTM ถึง PPSM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-pps/" name="DOTM ถึง PPS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-odp/" name="DOTM ถึง ODP" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}