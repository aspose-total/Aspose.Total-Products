---
title: อัปเดตไฟล์ Excel โดยใช้ .NET 

description: แก้ไขเอกสาร Microsoft Excel XLSX, XLS, CSV โดยไม่ต้องติดตั้ง Microsoft Office ด้วยแอปพลิเคชันที่ใช้ C# .NET
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="อัปเดตเอกสาร Excel ผ่าน .NET" h2="แก้ไขไฟล์ Microsoft Excel XLSX, XLS ภายในแอปพลิเคชันที่ใช้ .NET โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}
เป็นเรื่องปกติที่องค์กรจะอัปเดตข้อมูลของตน จัดเก็บไว้ในไฟล์ excel เช่น ข้อมูลนักเรียน บันทึกผู้ป่วย และรายการคลังสินค้า ฯลฯ ผ่านซอฟต์แวร์ของบริษัท [Aspose.Total for .NET](https://products.aspose.com/total/net/) API มีฟังก์ชันการแก้ไขสเปรดชีตโดยใช้ซอฟต์แวร์ โปรแกรมเมอร์สามารถปรับปรุงซอฟต์แวร์ด้วยความสามารถในการปรับเปลี่ยนโดยการเขียนโค้ด API เพียงไม่กี่บรรทัด [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for .NET](https://products.aspose.com/total/net/) ทำให้กระบวนการแก้ไขนี้ง่ายขึ้น ด้านล่างนี้คือขั้นตอนการอัปเดตเอกสาร Excel
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="อัปเดตเอกสาร Excel โดยใช้ .NET" %}}

[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API มีคลาสสมุดงานที่จัดการการโหลดสเปรดชีต Excel กระบวนการนั้นง่าย สร้างวัตถุ [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) โดยระบุไฟล์ต้นฉบับเป็นพารามิเตอร์ เข้าถึงแผ่นงานที่เกี่ยวข้องโดยจัดทำดัชนีโดยใช้วิธี [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/) ใช้เมธอด [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) เพื่อแก้ไขเนื้อหาในเซลล์ที่เข้าถึง และสุดท้ายเรียกเมธอด save() เพื่อบันทึกเอกสาร

{{% blocks/products/pf/feature-page-code h3=".NET Code - อัปเดตเอกสาร Excel" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="อัปเดต">}}