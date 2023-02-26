---
title: แปลง ODT เป็น TSV โดยใช้ Python หรือด้วยตัวแปลงออนไลน์ฟรี
description: การแปลง ODT เป็น TSV ในแอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Word หรือ Excel หรือทางออนไลน์ ทดสอบตัวแปลง CSV เป็น POT ออนไลน์ฟรีอย่างรวดเร็วก่อนที่จะรวมโค้ด 

family: total
platformtag: Python
feature: conversion
informat: ODT
outformat: TSV
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง ODT เป็น TSV ผ่าน Python หรือทางออนไลน์" h2="การแปลง ODT เป็น TSV ในแอปพลิเคชัน Python โดยไม่ต้องติดตั้ง Microsoft Word<sup>&reg;</sup> หรือ Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ที่พยายามเพิ่มคุณสมบัติการแปลง ODT เป็น TSV ภายในแอปพลิเคชัน [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API สามารถช่วยทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่เกี่ยวข้องกับรูปแบบต่างๆ

ส่วนใหญ่อยู่ในสองขั้นตอน ขั้นแรกให้ใช้ [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API เพื่อแปลงไฟล์ ODT เป็น HTML หลังจากนั้นโดยใช้ Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) ให้บันทึก HTML ที่สร้างขึ้นเป็นรูปแบบ Microsoft Excel ที่ต้องการ 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง ODT เป็น TSV ใน Python" %}}
- **ขั้นตอนที่ 1** เปิดไฟล์ ODT ต้นทางโดยใช้คลาส [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- บันทึกไฟล์ ODT เป็น HTML โดยใช้วิธี [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) โดยระบุชื่อไฟล์และเส้นทางไดเร็กทอรีที่ต้องการ
-  **ขั้นตอนที่ 2** โหลดไฟล์ HTML ด้วยอินสแตนซ์ของคลาสสมุดงานที่มีไฟล์และ LoadOptions เป็นพารามิเตอร์
-  เรียกใช้เมธอด "save" ขณะระบุพาธไฟล์ TSV เอาต์พุต ดังนั้นไฟล์ ODT ของคุณจึงถูกแปลงเป็น TSV ตามเส้นทางที่ระบุ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลง ODT เป็น TSV จำเป็นต้องใช้ Python 3.5 หรือใหม่กว่า
- อ้างอิง API ภายในโครงการโดยตรงจาก PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) และ [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.words``` และ ```pip install aspose-cells-python``` 
-  นอกจากนี้ ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux (ดูเพิ่มเติมสำหรับ [Words](https://docs.aspose.com/words/python-net/system-requirements/) และ [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) และสำหรับ Linux ตรวจสอบข้อกำหนดเพิ่มเติมสำหรับ gcc และ libpython และปฏิบัติตาม [คำแนะนำทีละขั้นตอน](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="บันทึก ODT เป็น HTML ใน Python - ขั้นตอนที่ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="บันทึก HTML เป็น TSV ใน Python - ขั้นตอนที่ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>ตัวแปลงออนไลน์ฟรีสำหรับ ODT เป็น TSV</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=tsv&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-excel/" name="ODT ถึง EXCEL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-xls/" name="ODT ถึง XLS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-xlsx/" name="ODT ถึง XLSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-csv/" name="ODT ถึง CSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-dif/" name="ODT ถึง DIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-fods/" name="ODT ถึง FODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-ods/" name="ODT ถึง ODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-sxc/" name="ODT ถึง SXC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-tsv/" name="ODT ถึง TSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-xlam/" name="ODT ถึง XLAM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-xlsb/" name="ODT ถึง XLSB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-xlt/" name="ODT ถึง XLT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-xltm/" name="ODT ถึง XLTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-xltx/" name="ODT ถึง XLTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-net/conversion/odt-to-xlsm/" name="ODT ถึง XLSM" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}