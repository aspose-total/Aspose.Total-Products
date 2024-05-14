---
title: ลบคำอธิบายประกอบ Excel ออนไลน์หรือจัดการคำอธิบายประกอบโดยใช้แอพมือถือ Android
description: ลบความคิดเห็นออกจากไฟล์ Excel ผ่านแอปออนไลน์ฟรีรหัส Android API เพื่อจัดการความคิดเห็นของไฟล์ Excel

family: total
platformtag: Android
feature: Annotate
informat: Excel
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="ล้างความคิดเห็นจากเอกสาร Excel ออนไลน์หรือจัดการผ่านแอพ Android" h2="พัฒนาแอปพลิเคชันยูทิลิตี้คำอธิบายประกอบเอกสาร Excel ที่ใช้ Android ที่ทรงพลังรหัสที่แสดงสำหรับการจัดการความคิดเห็นของไฟล์ Excel" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ลบคำอธิบายประกอบ Excel ออนไลน์" %}}

1. นำเข้าไฟล์ Excel เพื่อลบความคิดเห็นโดยการอัปโหลด
1. ทำได้โดยการคลิกภายในพื้นที่วางผ่านการลากและวางของแอปคำอธิบายประกอบ
1. ขึ้นอยู่กับขนาดของไฟล์ Excel และความเร็วอินเตอร์เน็ต ให้รอสักครู่
1. คลิกปุ่ม 'ลบ' เพื่อล้างความคิดเห็น
1. ดาวน์โหลดไฟล์ได้ทันที

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ลบความคิดเห็นเอกสาร Excel ผ่าน Android App API" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Android
1. โหลดเอกสารผ่านวัตถุคลาสสมุดงาน
1. เลือกแผ่นงานเฉพาะ
1. รับความคิดเห็นทั้งหมดจากการใช้ [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--)
1. รับความคิดเห็นแบบเธรดทั้งหมดผ่าน getThreadedComments
1. ใช้ RemoveAt เพื่อลบความคิดเห็นและผู้แต่งตามลำดับ
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส : ลบความคิดเห็นออกจากเอกสาร Excel" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="อัปเดตความคิดเห็น Excel ของเธรด" %}}

1. โหลดเอกสารผ่านวัตถุคลาสสมุดงาน
1. รับแผ่นงานเฉพาะ
1. รับความคิดเห็นแบบเธรดโดยใช้ getComments().getThreadedComments(Index).get(Index)
1. ใช้วิธี setNotes เพื่ออัปเดตความคิดเห็น
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="เพิ่มความคิดเห็นผ่าน Android App API" %}}

1. สร้างเอกสารผ่านวัตถุคลาสสมุดงาน
1. รับแผ่นงานเฉพาะ
1. เพิ่มดัชนีความคิดเห็นผ่าน getComments().add
1. ใช้เมธอด setNotes เพื่อเพิ่มความคิดเห็น
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์ with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส: อัปเดตความคิดเห็นแบบเธรดของไฟล์ Excel" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="รหัส: การเพิ่มความคิดเห็น" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>พัฒนาแอพ Android คำอธิบายประกอบเอกสาร Excel</h2>

ต้องการพัฒนาแอปหรือยูทิลิตี้คำอธิบายประกอบ Excel ที่ใช้ Android เพื่อให้ข้อเสนอแนะ ให้คำแนะนำ หรือทำงานร่วมกับผู้อื่นในเอกสารหรือไม่ด้วย [Aspose.Cells for Android via Java](https://products.aspose.com/cells/th/android-java/) ซึ่งเป็น API ลูกของ [Aspose.Total for Android via Java](https://products.aspose.com/total/th/android-java/) นักพัฒนา Android ทุกคนสามารถรวมโค้ด API ข้างต้นภายในแอปพลิเคชันคำอธิบายประกอบเอกสารได้ไลบรารี Android อันทรงพลังช่วยให้สามารถเขียนโปรแกรมโซลูชันคำอธิบายประกอบเอกสารได้นอกจากนี้ยังสามารถรองรับรูปแบบยอดนิยมมากมายรวมถึงรูปแบบ Excel<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API เพื่อใส่คำอธิบายประกอบไฟล์ Excel" %}}

- เราโฮสต์แพ็คเกจ Java ของเราใน [ที่เก็บ Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/) 
- Aspose.Cells for Java เป็นไฟล์ JAR ทั่วไปที่มีรหัสไบต์
- ทำตาม [คำแนะนำทีละขั้นตอน](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) เกี่ยวกับวิธีการติดตั้ง Aspose.Cells for Android via Java

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

- ระบบปฏิบัติการ Android 2.0 หรือสูงกว่า
- แพ็คเกจ Java เป็นแพลตฟอร์มข้ามแพลตฟอร์มและทำงานบนระบบปฏิบัติการทั้งหมดที่มีการใช้งาน JVM

<br />
สำหรับรายละเอียดเพิ่มเติม โปรดดูที่ [เอกสารประกอบผลิตภัณฑ์](https://docs.aspose.com/cells/java/system-requirements/)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}