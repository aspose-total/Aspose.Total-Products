---
title: อัปเดตไฟล์ Excel โดยใช้ C++ 

description: แก้ไขเอกสาร Microsoft Excel XLSX, XLS, CSV โดยไม่ต้องติดตั้ง Microsoft Office ด้วยแอปพลิเคชันที่ใช้ C++
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="อัปเดตเอกสาร Excel ผ่าน C++" h2="แก้ไขไฟล์ Microsoft Excel XLSX, XLS ภายในแอปพลิเคชันที่ใช้ C++ โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}
เป็นเรื่องปกติที่องค์กรจะอัปเดตข้อมูลของตน จัดเก็บไว้ในไฟล์ excel เช่น ข้อมูลนักเรียน บันทึกผู้ป่วย และรายการคลังสินค้า ฯลฯ ผ่านซอฟต์แวร์ของบริษัท [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API มีฟังก์ชันการแก้ไขสเปรดชีตโดยใช้ซอฟต์แวร์ โปรแกรมเมอร์สามารถปรับปรุงซอฟต์แวร์ด้วยความสามารถในการปรับเปลี่ยนโดยการเขียนโค้ด API เพียงไม่กี่บรรทัด [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) ทำให้กระบวนการแก้ไขนี้ง่ายขึ้น ด้านล่างนี้คือขั้นตอนการอัปเดตเอกสาร Excel
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="อัปเดตเอกสาร Excel โดยใช้ C++" %}}

ใช้ [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API โหลดเอกสารต้นฉบับโดยใช้ [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) เข้าถึง [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) โดยใช้ GetIWorksheets()->GetObjectByIndex(0) และเซลล์ที่ต้องการโดยใช้ GetICells()->GetObjectByIndex โดยใช้วิธี PutValue แก้ไขเนื้อหาในเซลล์ที่เข้าถึง สุดท้ายเรียกใช้เมธอด save() เพื่อบันทึกเอกสาร

{{% blocks/products/pf/feature-page-code h3="รหัส C ++ - อัปเดตเอกสาร Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="อัปเดต">}}