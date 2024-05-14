---
title: ลบคำอธิบายประกอบ PDF ออนไลน์หรือจัดการคำอธิบายประกอบโดยใช้แอพมือถือ Android
description: ลบความคิดเห็นออกจากไฟล์ PDF ผ่านแอปออนไลน์ฟรีรหัส Android API เพื่อจัดการความคิดเห็นของไฟล์ PDF

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="ล้างความคิดเห็นจากเอกสาร PDF ออนไลน์หรือจัดการผ่านแอพ Android" h2="พัฒนาแอปพลิเคชันอรรถประโยชน์คำอธิบายประกอบเอกสาร PDF ที่ใช้ Android ที่ทรงพลังรหัสที่แสดงสำหรับการจัดการความคิดเห็นของไฟล์ PDF" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ลบคำอธิบายประกอบ PDF ออนไลน์" %}}

1. นำเข้าไฟล์ PDF เพื่อลบความคิดเห็นโดยการอัปโหลด
1. ทำได้โดยการคลิกภายในพื้นที่วางผ่านการลากและวางของแอปคำอธิบายประกอบ
1. ขึ้นอยู่กับขนาดของไฟล์ PDF และความเร็วอินเตอร์เน็ต ให้รอสักครู่
1. คลิกปุ่ม 'ลบ' เพื่อล้างความคิดเห็น
1. ดาวน์โหลดไฟล์ได้ทันที

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ลบความคิดเห็นเอกสาร PDF ผ่าน Android App API" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Android
1. โหลดเอกสารผ่านวัตถุคลาสเอกสาร
1. เลือกหน้าเฉพาะผ่าน getPages().get_Item(Index)
1. ใช้ AnnotationSelector และรับคำอธิบายประกอบข้อความทั้งหมดผ่าน annotationSelector.getSelected()
1. วนซ้ำคำอธิบายประกอบแต่ละรายการโดยเรียกใช้เมธอด Delete เพื่อลบออก
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส : ลบความคิดเห็นออกจากไฟล์ PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="เพิ่มคำอธิบายประกอบผ่าน Android App API" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Android
1. สร้างวัตถุคลาสเอกสาร
1. เพิ่มหน้าใหม่และเนื้อหาโดยใช้ getPages().add()
1. ใช้ getPages().get_Item(Index) ของคลาส TextAnnotation
1. กำหนดคำอธิบายประกอบที่เกี่ยวข้อง เช่น ชื่อเรื่อง หัวเรื่อง เนื้อหา ฯลฯ
1. ใช้ getAnnotations().add เพื่อเพิ่มคำอธิบายประกอบ
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์พร้อมความคิดเห็นเพิ่มเติม
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส : เพิ่มคำอธิบายประกอบ PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>พัฒนาแอพ Android คำอธิบายประกอบเอกสาร PDF</h2>

ต้องการพัฒนาแอปหรือยูทิลิตี้คำอธิบายประกอบ PDF บนมือถือเพื่อให้คำติชม ให้คำแนะนำ หรือทำงานร่วมกับผู้อื่นในเอกสารหรือไม่ด้วย [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/th/android-java/) ซึ่งเป็น API ลูกของ [Aspose.Total for Android via Java](https://products.aspose.com/total/th/android-java/) นักพัฒนา Android ทุกคนสามารถรวมโค้ด API ข้างต้นภายในแอปพลิเคชันคำอธิบายประกอบเอกสารได้ไลบรารี Android อันทรงพลังช่วยให้สามารถเขียนโปรแกรมโซลูชันคำอธิบายประกอบเอกสารได้นอกจากนี้ยังสามารถรองรับรูปแบบยอดนิยมมากมายรวมถึงรูปแบบ PDF<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ไลบรารี Android เพื่อใส่คำอธิบายประกอบไฟล์ PDF" %}}

- เราโฮสต์แพ็คเกจ Java ของเราใน [ที่เก็บ Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/) 
- Aspose.PDF for Java เป็นไฟล์ JAR ทั่วไปที่มีรหัสไบต์
- ทำตาม [คำแนะนำทีละขั้นตอน](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) เกี่ยวกับวิธีการติดตั้ง Aspose.PDF for Android via Java

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

- ระบบปฏิบัติการ Android API 31 และ 32
- ระบบปฏิบัติการ Android 4.0 ขึ้นไป
- เครื่องมือ Android Studio และ SDK

<br />
สำหรับรายละเอียดเพิ่มเติมเกี่ยวกับการขึ้นต่อกันของแพ็คเกจเสริม เช่น JogAmp JOGL, เอ็นจิ้นแบบอักษร Harfbuzz, Java Advanced Imaging JAI โปรดดูที่ [เอกสารประกอบผลิตภัณฑ์](https://docs.aspose.com/pdf/java/system-requirements/)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}