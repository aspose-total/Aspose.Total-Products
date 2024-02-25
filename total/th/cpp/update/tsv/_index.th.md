---
title: อัปเดตไฟล์ TSV โดยใช้ C++
description: แก้ไขเอกสาร TSV ในแอปพลิเคชัน C++ โดยไม่ต้องใช้ Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="อัปเดตไฟล์ TSV ผ่าน C++" h2="แก้ไขสเปรดชีต TSV ผ่านแอปพลิเคชันที่ใช้ C++ โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับโปรแกรมเมอร์ที่กำลังพยายามอัปเดตไฟล์ TSV ภายในแอปพลิเคชัน C++, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API สามารถช่วยให้กระบวนการอัปเดตเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของไลบรารี C++ ที่แตกต่างกันซึ่งมีหลายรูปแบบรวมถึงเอกสาร Microsoft Excel [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for C++](https://products.aspose.com/total/cpp/) ทำให้กระบวนการแก้ไขนี้ง่ายขึ้น ขั้นตอนการอัปเดตเอกสาร TSV ทำได้ง่ายโดยเข้าไปที่ชีตก่อน จากนั้นจึงอัปเดตค่าเซลล์ใน excel โดยใช้ C++

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีอัปเดตไฟล์ TSV ใน C++" %}}

- โหลดไฟล์ TSV โดยใช้ [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- การเข้าถึง [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) ที่เกี่ยวข้องโดยใช้ GetIWorksheets()->GetObjectByIndex(0) และเซลล์ที่เกี่ยวข้องโดยใช้ GetICells()->GetObjectByIndex
- แทรกข้อมูลใหม่ในเซลล์ที่เข้าถึงโดยใช้วิธี PutValue
- บันทึกไฟล์เป็นไฟล์ .tsv โดยใช้วิธีบันทึกโดยส่งไฟล์ที่มีพาธเป็นพารามิเตอร์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการปรับเปลี่ยน" %}}

- สำหรับการแก้ไข TSV ให้ทำตาม [ความต้องการของระบบ](https://docs.aspose.com/cells/cpp/system-requirements/) สำหรับระบบ Windows และ Linux 
- ติดตั้งจากบรรทัดคำสั่งเป็น ``` nuget install Aspose.Total.Cpp```
- หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Total.Cpp```
- หรืออีกทางหนึ่ง รับตัวติดตั้ง MSI หรือ DLL แบบออฟไลน์ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="รหัส - อัปเดตไฟล์ TSV ใน C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}