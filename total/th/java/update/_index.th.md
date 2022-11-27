---
title: อัปเดตไฟล์ Excel โดยใช้ Java 

description: แก้ไขเอกสาร Microsoft Excel XLSX, XLS, CSV โดยไม่ต้องติดตั้ง Microsoft Office ภายในแอปพลิเคชันที่ใช้ Java
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="อัปเดตเอกสาร Excel ผ่าน Java" h2="แก้ไขไฟล์ Microsoft Excel XLSX, XLS ภายในแอปพลิเคชันที่ใช้ Java โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}
เป็นเรื่องปกติที่องค์กรจะอัปเดตข้อมูลของตน จัดเก็บไว้ในไฟล์ excel เช่น ข้อมูลนักเรียน บันทึกผู้ป่วย และรายการคลังสินค้า ฯลฯ ผ่านซอฟต์แวร์ของบริษัท [Aspose.Total for Java](https://products.aspose.com/total/java/) API มีฟังก์ชันการแก้ไขสเปรดชีตโดยใช้ซอฟต์แวร์ของตนเอง โปรแกรมเมอร์สามารถปรับปรุงซอฟต์แวร์ด้วยความสามารถในการปรับเปลี่ยนโดยการเขียนโค้ด API เพียงไม่กี่บรรทัด [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/) ทำให้กระบวนการแก้ไขนี้ง่ายขึ้น ด้านล่างนี้คือขั้นตอนการอัปเดตเอกสาร Excel
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="อัปเดตเอกสาร Excel โดยใช้ Java" %}}

[Aspose.Cells for Java](https://products.aspose.com/cells/java/) API มีคลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ที่จัดการการโหลดสเปรดชีต Excel กระบวนการนั้นง่าย สร้างวัตถุคลาสเวิร์กบุ๊กโดยระบุไฟล์ต้นฉบับเป็นพารามิเตอร์ เข้าถึงแผ่นงานที่เกี่ยวข้องและเซลล์ที่เกี่ยวข้องโดยใช้วิธี [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)) ใช้เมธอด [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) เพื่อแก้ไขเนื้อหาในเซลล์ที่เข้าถึง และสุดท้ายเรียกเมธอด save() เพื่อบันทึกเอกสาร

{{% blocks/products/pf/feature-page-code h3="รหัส Java - อัปเดตเอกสาร Excel" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="อัปเดต">}}