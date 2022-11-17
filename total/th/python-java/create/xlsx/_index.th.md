---
title: สร้าง XLSX ใน Python
description: สร้างไฟล์ XLSX โดยใช้แอปพลิเคชัน Python โดยไม่ต้องใช้ Microsoft Office 

family: total
platformtag: Python
feature: create
informat: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="สร้าง XLSX โดยใช้ Python" h2="สร้าง XLSX ผ่านแอปพลิเคชัน Python โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนาที่กำลังพยายามสร้างไฟล์ XLSX ผ่านแอพพลิเคชั่น Python? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API สามารถช่วยทำให้กระบวนการสร้างเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่จัดการรูปแบบต่างๆ รวมถึงไฟล์ Microsoft Office และรูปภาพ [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) ทำให้กระบวนการสร้างนี้ง่ายขึ้น ด้านล่างนี้คือกระบวนการสร้าง นอกจากนี้ นักพัฒนายังสามารถปรับปรุงแอปพลิเคชันเพื่อแก้ไขไฟล์ XLSX ได้อย่างง่ายดาย หากต้องการอัปเดตไฟล์ XLSX โดยใช้กระบวนการ Python จะเหมือนกัน ยกเว้นว่าต้องการไฟล์ที่มีอยู่เป็นพารามิเตอร์ขณะสร้างวัตถุ Workbook

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีสร้างไฟล์ XLSX ใน Python" %}}

- สร้างคลาสอ็อบเจ็กต์ [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) ใหม่ที่มี ไฟล์FormatType เป็นพารามิเตอร์
- รับการเข้าถึง [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) ที่ต้องการโดยใช้วิธี [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- แทรกข้อมูลในเซลล์ที่เข้าถึงโดยใช้วิธี [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- บันทึกเอกสารเป็นไฟล์ .xlsx โดยใช้ [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String) โดยส่งไฟล์ที่มีเส้นทางเป็นพารามิเตอร์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการสร้าง" %}}

- สำหรับการสร้าง XLSX อ้างอิง API ภายในโปรเจ็กต์โดยตรงจาก PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.cells``` 
- นอกจากนี้ ดาวน์โหลดแพ็คเกจ API จากส่วน [downloads](https://downloads.aspose.com/cells/python-java) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="สร้าง XLSX ใน Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-java/create/xls/" name="สร้าง XLS ไฟล์" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-java/create/xlsx/" name="สร้าง XLSX ไฟล์" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-java/create/csv/" name="สร้าง CSV ไฟล์" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-java/create/xlsb/" name="สร้าง XLSB ไฟล์" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-java/create/xlsm/" name="สร้าง XLSM ไฟล์" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-java/create/xlt/" name="สร้าง XLT ไฟล์" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-java/create/xltx/" name="สร้าง XLTX ไฟล์" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-java/create/xltm/" name="สร้าง XLTM ไฟล์" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-java/create/ods/" name="สร้าง ODS ไฟล์" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/th/python-java/create/tsv/" name="สร้าง TSV ไฟล์" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}