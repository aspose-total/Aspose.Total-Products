---
title: อัปเดตไฟล์ XLT โดยใช้ Python
description: แก้ไขเอกสาร XLT ในแอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Excel 

family: total
platformtag: Python
feature: update
informat: XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="อัปเดตไฟล์ XLT ผ่าน Python" h2="แก้ไขสเปรดชีต XLT ผ่านแอปพลิเคชัน Python โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนาที่กำลังพยายามอัพเดทไฟล์ XLT ผ่านแอพพลิเคชั่น Python? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API สามารถช่วยทำให้กระบวนการอัปเดตเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่จัดการรูปแบบต่างๆ รวมถึงไฟล์ Microsoft Excel ASPOSE.CELL API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) ทำให้กระบวนการแก้ไขนี้ง่ายขึ้น ด้านล่างนี้เป็นกระบวนการอัปเดตเอกสาร XLT

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีอัปเดตไฟล์ XLT ใน Python" %}}

- สร้างวัตถุคลาส [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) ใหม่ที่มีไฟล์ XLT ต้นทางเป็นพารามิเตอร์
- การเข้าถึงแผ่นงานที่เกี่ยวข้องโดยใช้วิธี [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- แทรกข้อมูลใหม่ในเซลล์ที่เข้าถึงโดยใช้วิธี [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- บันทึกไฟล์เป็นไฟล์ .xlt โดยใช้เมธอด save() โดยส่งไฟล์ที่มีพาธเป็นพารามิเตอร์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการปรับเปลี่ยน" %}}

- สำหรับการแก้ไข XLT อ้างอิง API ภายในโปรเจ็กต์โดยตรงจาก PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.cells``` 
- นอกจากนี้ ดาวน์โหลดแพ็คเกจ API จากส่วน [ดาวน์โหลด](https://releases.aspose.com/cells/python-java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="รหัส - อัปเดตไฟล์ XLT ใน Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}