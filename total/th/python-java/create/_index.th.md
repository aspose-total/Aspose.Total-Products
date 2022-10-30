---
title: สร้างและอัปเดตไฟล์ Microsoft Excel โดยใช้ Python 
url: /th/python-java/create/
description: สร้างรายงานเวิร์กชีต Microsoft Excel โดยไม่ต้องติดตั้ง Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="สร้างรายงาน Excel โดยใช้ Python" h2="สร้างและอัปเดตเอกสาร Microsoft Excel Spreadsheet XLS, XLSX ภายใน Python Applications โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) เป็น Python API สำหรับสร้าง อ่าน และเขียนเอกสารในรูปแบบ Microsoft Excel รวมถึง XLS และ XLSX API นี้เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) นอกจากนี้ นักพัฒนาซอฟต์แวร์ยังสามารถเขียนโค้ดสำหรับการแทรกข้อมูล รูปภาพ แผนภูมิ ตาราง Pivot ภายในเวิร์กชีตและฟังก์ชันอื่นๆ อีกมากมายได้อย่างง่ายดาย Python API ยังรองรับคุณสมบัติต่างๆ เช่น ตั้งค่า [สูตร](https://docs.aspose.com/cells/python-java/supported-formula-functions/) ต่างๆ แปลงข้อความเป็นคอลัมน์ ตัวทำเครื่องหมายอัจฉริยะ และตัวเลือกสูตรแบบไดนามิก ด้านล่างนี้คือโค้ดตัวอย่างบางส่วนในการสร้างและแก้ไขสเปรดชีต

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="วิธีสร้างไฟล์ Excel โดยใช้ Python" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API จัดเตรียมคลาสเวิร์กบุ๊กที่จัดการการสร้างไฟล์ กระบวนการนั้นง่าย สร้างวัตถุคลาสเวิร์กบุ๊กและเข้าถึงเวิร์กชีตที่เกี่ยวข้องโดยระบุดัชนี ใช้เมธอด putValue เพื่อเพิ่มเนื้อหาในเซลล์ที่เข้าถึง และสุดท้ายเรียกเมธอด save() เพื่อบันทึกเอกสารด้วยชื่อเฉพาะ

{{% blocks/products/pf/feature-page-code h3="รหัส 1 - สร้างไฟล์ Excel อย่างง่าย" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="รหัส 2 - แทรกรูปภาพภายในเอกสาร Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="วิธีอัปเดตไฟล์ Microsoft Excel โดยใช้ Python" %}}

ขั้นตอนการสร้างและอัปเดตไฟล์ Excel เกือบจะเหมือนกัน ยกเว้นข้อแตกต่างเพียงอย่างเดียว ความแตกต่างคือ ระหว่างกระบวนการสร้าง วัตถุสมุดงานว่างเปล่าจะถูกสร้างขึ้นในขณะที่อยู่ระหว่างกระบวนการอัปเดต จำเป็นต้องมีไฟล์ Excel ที่มีอยู่ ดังนั้นส่งไฟล์ที่มีอยู่เป็นพารามิเตอร์ไปยังคลาสสมุดงาน ส่วนที่เหลือขั้นตอนเหมือนกัน

{{% blocks/products/pf/feature-page-code h3="รหัส 3 - อัปเดตเอกสาร Microsoft Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}