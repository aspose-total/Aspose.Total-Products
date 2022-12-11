---
title: แปลง TSV เป็น ODT โดยใช้ Python
description: การแปลง TSV เป็น ODT ในแอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: TSV
outformat: ODT
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง TSV เป็น ODT ผ่าน Python" h2="การแปลง TSV เป็น ODT ในแอปพลิเคชัน Python โดยไม่ต้องติดตั้ง Microsoft Excel<sup>&reg;</sup> หรือ Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ที่พยายามเพิ่มคุณสมบัติการแปลง TSV เป็น ODT ภายในแอปพลิเคชัน [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่เกี่ยวข้องกับรูปแบบต่างๆ รวมถึงไฟล์ TSV และ ODT

ส่วนใหญ่อยู่ในสองขั้นตอน ขั้นแรกให้ใช้ [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API เพื่อแปลงไฟล์ TSV เป็น HTML หลังจากนั้นโดยใช้ Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) ให้บันทึก HTML ที่สร้างขึ้นเป็นรูปแบบ Microsoft Word ที่ต้องการ 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง TSV เป็น ODT ใน Python" %}}
- **ขั้นตอนที่ 1** เปิดไฟล์ TSV ต้นทางโดยใช้คลาส Workbook
- บันทึกไฟล์ TSV เป็น HTML โดยใช้วิธี save(file, SaveFormat.HTML) โดยระบุชื่อไฟล์และเส้นทางไดเร็กทอรีที่ต้องการ
-  **ขั้นตอนที่ 2** โหลดไฟล์ HTML ด้วยอินสแตนซ์ของคลาส [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  เรียกใช้เมธอด "save" ขณะระบุพาธไฟล์ ODT เอาต์พุต ดังนั้นไฟล์ TSV ของคุณจึงถูกแปลงเป็น ODT ตามเส้นทางที่ระบุ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลง TSV เป็น ODT จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) และ [Aspose.Words](https://pypi.org/project/aspose-words/))
-  หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose-cells-python``` และ ```pip install aspose.words```
-  นอกจากนี้ ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) และ [Words](https://docs.aspose.com/words/python-net/system-requirements/)) และสำหรับ Linux ตรวจสอบข้อกำหนดเพิ่มเติมสำหรับ gcc และ libpython และปฏิบัติตาม [คำแนะนำทีละขั้นตอน](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="บันทึก TSV เป็น HTML ใน Python - ขั้นตอนที่ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="บันทึก HTML เป็น ODT ใน Python - ขั้นตอนที่ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}