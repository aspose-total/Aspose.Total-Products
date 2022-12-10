---
title: แปลง XLSB เป็นรูปภาพโดยใช้ Python
description: XLSB เป็นรูปภาพ TIFF BMP PNG JPEG GIF EMF การแปลง SVG ในแอปพลิเคชัน Python ของคุณโดยไม่ต้องใช้ Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: XLSB
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แปลง XLSB เป็นรูปภาพผ่าน Python" h2="การแปลงรูปภาพ XLSB เป็น JPG, TIFF, BMP, PNG, GIF ในแอปพลิเคชัน Python ของคุณโดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนา Python ที่กำลังพยายามเพิ่มคุณสมบัติการแปลง XLSB ให้กับ PNG, BMP, TIFF, JPEG และ GIF Image ภายในแอปพลิเคชัน ในบางครั้ง จำเป็นต้องฝังสเปรดชีต Excel ในแอปพลิเคชันบนเว็บหรือเดสก์ท็อป ในกรณีเช่นนี้ การส่งออกสเปรดชีตไปยังรูปภาพถือเป็นหัวใจสำคัญอย่างหนึ่ง [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API สามารถช่วยในการส่งออกไฟล์ Excel ไปยังรูปภาพรวมทั้งทำให้กระบวนการแปลงเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ API ต่างๆ ที่จัดการรูปแบบต่างๆ รวมถึงรูปแบบ Microsoft Excel ผ่าน [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API ย่อย ปัจจุบัน Python Excel เป็น Image Converter API รองรับการแปลงไฟล์ Excel เป็น EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM และ Office Compatible EMF หรือตรวจสอบ [รูปแบบ](https://docs.aspose.com/cells/python-java/supported-file-formats/) ที่รองรับ 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลง XLSB เป็นรูปภาพใน Python" %}}

- สร้างคลาสอ็อบเจ็กต์ [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) เพื่อโหลดไฟล์ XLSB
- ใช้คลาส [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) และระบุตัวเลือกที่เกี่ยวข้องกับรูปภาพที่ส่งออก
- เข้าถึงแผ่นงานสำหรับการแปลงโดยใช้วิธี [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- บันทึกทุกหน้าของแผ่นงานเป็นรูปภาพโดยใช้วิธี [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)) ตอนนี้ไฟล์ XLSB ถูกแปลงเป็นรูปภาพตามเส้นทางที่ระบุ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}

- สำหรับการแปลง XLSB เป็นรูปภาพ (JPG, PNG, GIF, BMP, TIFF) ให้อ้างอิง API ภายในโปรเจ็กต์โดยตรงจาก PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- หรือใช้คำสั่ง pip ต่อไปนี้ ```pip install aspose.cells``` 
- นอกจากนี้ ดาวน์โหลดแพ็คเกจ API จากส่วน [ดาวน์โหลด](https://releases.aspose.com/cells/python-java) 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSB เป็นการแปลงรูปภาพผ่าน Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-net/conversion/excel-to-images/" name="EXCEL TO รูปภาพ" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/bmp1-to-images/" name="XLSB TO รูปภาพ" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/json-to-images/" name="JSON TO รูปภาพ" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/tsv-to-images/" name="TSV TO รูปภาพ" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xlsb-to-images/" name="XLSB TO รูปภาพ" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xlsm-to-images/" name="XLSM TO รูปภาพ" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xls-to-images/" name="XLS TO รูปภาพ" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xlsx-to-images/" name="XLSX TO รูปภาพ" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xltm-to-images/" name="XLTM TO รูปภาพ" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xlt-to-images/" name="XLT TO รูปภาพ" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/python-java/conversion/xltx-to-images/" name="XLTX TO รูปภาพ" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}