---
title: อัปเดตไฟล์ Excel โดยใช้ Python 

description: แก้ไขเอกสาร Microsoft Excel XLSX, XLS, CSV โดยไม่ต้องติดตั้ง Microsoft Office ภายในแอปพลิเคชัน Python
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="อัปเดตเอกสาร Excel ผ่าน Python" h2="แก้ไขไฟล์ Microsoft Excel XLSX, XLS ภายใน Python Applications โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}
เป็นเรื่องปกติที่องค์กรจะอัปเดตข้อมูลของตน จัดเก็บไว้ในไฟล์ excel เช่น ข้อมูลนักเรียน บันทึกผู้ป่วย และรายการคลังสินค้า เป็นต้น ผ่านซอฟต์แวร์ของบริษัท [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API มีฟังก์ชันการแก้ไขสเปรดชีตผ่านซอฟต์แวร์ โปรแกรมเมอร์สามารถปรับปรุงซอฟต์แวร์ด้วยความสามารถในการปรับเปลี่ยนโดยการรวม API และเขียนโค้ดไม่กี่บรรทัด [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) ทำให้กระบวนการแก้ไขนี้ง่ายขึ้น ด้านล่างนี้คือขั้นตอนการอัปเดตเอกสาร Excel
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="อัปเดตเอกสาร Excel โดยใช้ Python" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API มีคลาสสมุดงานที่จัดการการโหลดสเปรดชีต Excel กระบวนการนั้นง่าย สร้างวัตถุคลาส [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) โดยระบุไฟล์ต้นฉบับเป็นพารามิเตอร์ ใช้วิธี [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) เพื่อเข้าถึงแผ่นงานที่เกี่ยวข้องโดยระบุดัชนี เรียกใช้เมธอด [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) เพื่อแก้ไขเนื้อหาในเซลล์ที่เข้าถึง และเรียกใช้เมธอด save() เพื่อบันทึกเอกสาร

{{% blocks/products/pf/feature-page-code h3="Python - อัปเดตเอกสาร Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="อัปเดต">}}