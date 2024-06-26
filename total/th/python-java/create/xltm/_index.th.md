---
title: สร้าง XLTM ใน Python
description: สร้างไฟล์ XLTM โดยใช้แอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Office 

family: total
platformtag: Python
feature: create
informat: XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="สร้าง XLTM โดยใช้ Python" h2="สร้าง XLTM ผ่านแอปพลิเคชัน Python โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนาที่กำลังพยายามสร้างไฟล์ XLTM ผ่านแอพพลิเคชั่น Python? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API สามารถช่วยทำให้กระบวนการสร้างเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่จัดการรูปแบบต่างๆ รวมถึงไฟล์ Microsoft Office และรูปภาพ [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) ทำให้กระบวนการสร้างนี้ง่ายขึ้น ด้านล่างนี้คือกระบวนการสร้าง นอกจากนี้ นักพัฒนายังสามารถปรับปรุงแอปพลิเคชันเพื่อแก้ไขไฟล์ XLTM ได้อย่างง่ายดาย หากต้องการอัปเดตไฟล์ XLTM โดยใช้กระบวนการ Python จะเหมือนกัน ยกเว้นว่าต้องการไฟล์ที่มีอยู่เป็นพารามิเตอร์ขณะสร้างวัตถุ Workbook

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีสร้างไฟล์ XLTM ใน Python" %}}

- สร้างคลาสอ็อบเจ็กต์ [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) ใหม่ที่มี ไฟล์FormatType เป็นพารามิเตอร์
- รับการเข้าถึง [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) ที่ต้องการโดยใช้วิธี [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- แทรกข้อมูลในเซลล์ที่เข้าถึงโดยใช้วิธี [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- บันทึกเอกสารเป็นไฟล์ .xltm โดยใช้ [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String)) โดยส่งไฟล์ที่มีเส้นทางเป็นพารามิเตอร์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการสร้าง" %}}

- สำหรับการสร้าง XLTM อ้างอิง API ภายในโปรเจ็กต์โดยตรงจาก PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.cells``` 
- นอกจากนี้ ดาวน์โหลดแพ็คเกจ API จากส่วน [downloads](https://releases.aspose.com/cells/python-java) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="สร้าง XLTM ใน Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}