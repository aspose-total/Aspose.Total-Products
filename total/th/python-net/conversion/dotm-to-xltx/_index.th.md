---
title: แปลง DOTM เป็น XLTX โดยใช้ Python
description: การแปลง DOTM เป็น XLTX ในแอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Word หรือ Excel 

family: total
platformtag: Python
feature: conversion
informat: DOTM
outformat: XLTX
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง DOTM เป็น XLTX ผ่าน Python" h2="การแปลง DOTM เป็น XLTX ในแอปพลิเคชัน Python โดยไม่ต้องติดตั้ง Microsoft Word<sup>&reg;</sup> หรือ Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ที่พยายามเพิ่มคุณสมบัติการแปลง DOTM เป็น XLTX ภายในแอปพลิเคชัน [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่เกี่ยวข้องกับรูปแบบต่างๆ

ส่วนใหญ่อยู่ในสองขั้นตอน ขั้นแรกให้ใช้ [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API เพื่อแปลงไฟล์ DOTM เป็น HTML หลังจากนั้นโดยใช้ Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) ให้บันทึก HTML ที่สร้างขึ้นเป็นรูปแบบ Microsoft Excel ที่ต้องการ 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง DOTM เป็น XLTX ใน Python" %}}
- **ขั้นตอนที่ 1** เปิดไฟล์ DOTM ต้นทางโดยใช้คลาส [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- บันทึกไฟล์ DOTM เป็น HTML โดยใช้วิธี [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) โดยระบุชื่อไฟล์และเส้นทางไดเร็กทอรีที่ต้องการ
-  **ขั้นตอนที่ 2** โหลดไฟล์ HTML ด้วยอินสแตนซ์ของคลาสสมุดงานที่มีไฟล์และ LoadOptions เป็นพารามิเตอร์
-  เรียกใช้เมธอด "save" ขณะระบุพาธไฟล์ XLTX เอาต์พุต ดังนั้นไฟล์ DOTM ของคุณจึงถูกแปลงเป็น XLTX ตามเส้นทางที่ระบุ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลง DOTM เป็น XLTX จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) และ [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.words``` และ ```pip install aspose-cells-python``` 
-  นอกจากนี้ ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Words](https://docs.aspose.com/words/python-net/system-requirements/) และ [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) และสำหรับ Linux ตรวจสอบข้อกำหนดเพิ่มเติมสำหรับ gcc และ libpython และปฏิบัติตาม [คำแนะนำทีละขั้นตอน](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="บันทึก DOTM เป็น HTML ใน Python - ขั้นตอนที่ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="บันทึก HTML เป็น XLTX ใน Python - ขั้นตอนที่ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-excel/" name="DOTM ถึง EXCEL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-xls/" name="DOTM ถึง XLS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-xlsx/" name="DOTM ถึง XLSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-csv/" name="DOTM ถึง CSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-dif/" name="DOTM ถึง DIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-fods/" name="DOTM ถึง FODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-ods/" name="DOTM ถึง ODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-sxc/" name="DOTM ถึง SXC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-tsv/" name="DOTM ถึง TSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-xlam/" name="DOTM ถึง XLAM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-xlsb/" name="DOTM ถึง XLSB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-xlt/" name="DOTM ถึง XLT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-xltm/" name="DOTM ถึง XLTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-xltx/" name="DOTM ถึง XLTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/dotm-to-xlsm/" name="DOTM ถึง XLSM" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}