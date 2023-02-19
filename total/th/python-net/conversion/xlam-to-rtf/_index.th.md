---
title: แปลง XLAM เป็น RTF โดยใช้ Python
description: การแปลง XLAM เป็น RTF ในแอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLAM
outformat: RTF
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง XLAM เป็น RTF ผ่าน Python" h2="การแปลง XLAM เป็น RTF ในแอปพลิเคชัน Python โดยไม่ต้องติดตั้ง Microsoft Excel<sup>&reg;</sup> หรือ Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ที่พยายามเพิ่มคุณสมบัติการแปลง XLAM เป็น RTF ภายในแอปพลิเคชัน [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่เกี่ยวข้องกับรูปแบบต่างๆ รวมถึงไฟล์ XLAM และ RTF

ส่วนใหญ่อยู่ในสองขั้นตอน ขั้นแรกให้ใช้ [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API เพื่อแปลงไฟล์ XLAM เป็น HTML หลังจากนั้นโดยใช้ Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) ให้บันทึก HTML ที่สร้างขึ้นเป็นรูปแบบ Microsoft Word ที่ต้องการ 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง XLAM เป็น RTF ใน Python" %}}
- **ขั้นตอนที่ 1** เปิดไฟล์ XLAM ต้นทางโดยใช้คลาส Workbook
- บันทึกไฟล์ XLAM เป็น HTML โดยใช้วิธี save(file, SaveFormat.HTML) โดยระบุชื่อไฟล์และเส้นทางไดเร็กทอรีที่ต้องการ
-  **ขั้นตอนที่ 2** โหลดไฟล์ HTML ด้วยอินสแตนซ์ของคลาส [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  เรียกใช้เมธอด "save" ขณะระบุพาธไฟล์ RTF เอาต์พุต ดังนั้นไฟล์ XLAM ของคุณจึงถูกแปลงเป็น RTF ตามเส้นทางที่ระบุ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลง XLAM เป็น RTF จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) และ [Aspose.Words](https://pypi.org/project/aspose-words/))
-  หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose-cells-python``` และ ```pip install aspose.words```
-  นอกจากนี้ ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) และ [Words](https://docs.aspose.com/words/python-net/system-requirements/)) และสำหรับ Linux ตรวจสอบข้อกำหนดเพิ่มเติมสำหรับ gcc และ libpython และปฏิบัติตาม [คำแนะนำทีละขั้นตอน](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="บันทึก XLAM เป็น HTML ใน Python - ขั้นตอนที่ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="บันทึก HTML เป็น RTF ใน Python - ขั้นตอนที่ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ XLAM เป็น RTF</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=rtf&from=xlam" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-word/" name="XLAM ถึง WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-doc/" name="XLAM ถึง DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-docx/" name="XLAM ถึง DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-docm/" name="XLAM ถึง DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-dot/" name="XLAM ถึง DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-dotm/" name="XLAM ถึง DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-dotx/" name="XLAM ถึง DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-mobi/" name="XLAM ถึง MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-odt/" name="XLAM ถึง ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-ott/" name="XLAM ถึง OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-rtf/" name="XLAM ถึง RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/xlam-to-wordml/" name="XLAM ถึง WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}