---
title: อัปเดตไฟล์ XLT โดยใช้ Java
description: แก้ไขเอกสาร XLT ในแอปพลิเคชัน Java โดยไม่ต้องใช้ Microsoft Excel เพิ่มประสิทธิภาพโค้ดสำหรับวิธีที่เร็วที่สุดในการเขียนและแก้ไขไฟล์ excel ใน java

family: total
platformtag: Java
feature: update
informat: XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="อัปเดตไฟล์ XLT ผ่าน Java" h2="แก้ไขสเปรดชีต XLT ผ่านแอปพลิเคชันที่ใช้ Java โดยไม่ต้องติดตั้ง Microsoft Office<sup>&reg;</sup>" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับนักพัฒนาที่กำลังพยายามอัปเดตไฟล์ XLT ในแอปพลิเคชัน Java ใด ๆ [Aspose.Total for Java](https://products.aspose.com/total/java/) API สามารถช่วยทำให้กระบวนการอัปเดตเป็นไปโดยอัตโนมัติ เป็นแพ็คเกจเต็มรูปแบบของ Java API ต่างๆ ที่จัดการหลายรูปแบบ รวมถึงเอกสาร Microsoft Excel ASPOSE.CELL API ที่เป็นส่วนหนึ่งของแพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/) ทำให้กระบวนการแก้ไขนี้ง่ายขึ้น กระบวนการอัปเดตเอกสาร XLT นั้นง่ายโดยเข้าถึงชีตก่อนแล้วจึงอัปเดตค่าของเซลล์ใน excel โดยใช้ java

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="วิธีอัปเดตไฟล์ XLT ใน Java" %}}

- สร้างวัตถุคลาส [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ใหม่ที่มีไฟล์ XLT ต้นทางเป็นพารามิเตอร์
- การเข้าถึงแผ่นงานที่เกี่ยวข้องและเซลล์ที่เกี่ยวข้องโดยใช้วิธี [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int))
- แทรกข้อมูลใหม่ในเซลล์ที่เข้าถึงโดยใช้วิธี [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)
- บันทึกไฟล์เป็นไฟล์ .xlt โดยใช้เมธอด save() โดยส่งไฟล์ที่มีพาธเป็นพารามิเตอร์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการปรับเปลี่ยน" %}}

- สำหรับการปรับเปลี่ยน XLT, Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป.
- J2SE 6.0 (1.6), J2SE 7.0 (1.7) หรือสูงกว่า.
- รับ API เวอร์ชันล่าสุดโดยตรงจาก [ดาวน์โหลด](https://docs.aspose.com/cells/java/installation/)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="รหัส - อัปเดตไฟล์ XLT ใน Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}} 
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}