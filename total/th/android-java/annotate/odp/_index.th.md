---
title: ลบคำอธิบายประกอบ ODP ออนไลน์หรือจัดการคำอธิบายประกอบโดยใช้แอพมือถือ Android
description: ลบความคิดเห็นออกจากไฟล์ ODP ผ่านแอปออนไลน์ฟรีรหัส Android API เพื่อจัดการความคิดเห็นของไฟล์ ODP

family: total
platformtag: Android
feature: Annotate
informat: ODP
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="ล้างความคิดเห็นจากการนำเสนอ ODP ออนไลน์หรือจัดการผ่านแอพ Android" h2="พัฒนาแอปพลิเคชันอรรถประโยชน์คำอธิบายประกอบการนำเสนอ ODP ที่ใช้ Android ที่ทรงพลังรหัสที่แสดงสำหรับการจัดการความคิดเห็นของไฟล์ ODP" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ลบคำอธิบายประกอบ ODP ออนไลน์" %}}

1. นำเข้าไฟล์ ODP เพื่อลบความคิดเห็นโดยการอัปโหลด
1. ทำได้โดยการคลิกภายในพื้นที่วางผ่านการลากและวางของแอปคำอธิบายประกอบ
1. ขึ้นอยู่กับขนาดของไฟล์ ODP และความเร็วอินเตอร์เน็ต ให้รอสักครู่
1. คลิกปุ่ม 'ลบ' เพื่อล้างความคิดเห็น
1. ดาวน์โหลดไฟล์ได้ทันที

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ลบความคิดเห็นการนำเสนอ ODP ผ่านแอพ Android" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Android
1. โหลด ODP ผ่านวัตถุคลาสการนำเสนอ
1. วนซ้ำผู้เขียนแต่ละคนผ่านคอลเลกชัน Presentation.getCommentAuthors()
1. เรียกใช้วิธี clear() เพื่อลบความคิดเห็น
1. ในที่สุดก็เรียก getCommentAuthors().clear() เพื่อลบผู้เขียนทั้งหมด
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส : ลบความเห็นและผู้แต่งออกจากการนำเสนอ ODP" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="เพิ่มความคิดเห็นการนำเสนอ ODP ผ่านแอพ Android" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Android
1. โหลด ODP ผ่านวัตถุคลาสการนำเสนอ
1. เรียกใช้ Presentation.getCommentAuthors().addAuthor(String, String) เพื่อเพิ่มผู้เขียน
1. ใช้ ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date) สำหรับการเพิ่มความคิดเห็น
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์ with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส: การเพิ่มความคิดเห็น" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>พัฒนาแอพ Android คำอธิบายประกอบเอกสาร ODP</h2>

ต้องการพัฒนาแอปหรือยูทิลิตี้คำอธิบายประกอบ ODP บนมือถือเพื่อให้คำติชม ให้คำแนะนำ หรือทำงานร่วมกับผู้อื่นในเอกสารหรือไม่ด้วย [Aspose.Slides for Android via Java](https://products.aspose.com/slides/th/android-java/) ซึ่งเป็น API ลูกของ [Aspose.Total for Android via Java](https://products.aspose.com/total/th/android-java/) นักพัฒนา Android ทุกคนสามารถรวมโค้ด API ข้างต้นภายในแอปพลิเคชันคำอธิบายประกอบเอกสารได้ไลบรารี Android อันทรงพลังช่วยให้สามารถเขียนโปรแกรมโซลูชันคำอธิบายประกอบเอกสารได้นอกจากนี้ยังสามารถรองรับรูปแบบยอดนิยมมากมายรวมถึงรูปแบบ ODP<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ไลบรารี Android เพื่อใส่คำอธิบายประกอบไฟล์ ODP" %}}

- เราโฮสต์แพ็คเกจ Java ของเราใน [ที่เก็บ Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/) 
- Aspose.Slides for Java เป็นไฟล์ JAR ทั่วไปที่มีรหัสไบต์
- ทำตาม [คำแนะนำทีละขั้นตอน](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository) เกี่ยวกับวิธีการติดตั้ง Aspose.Slides for Android via Java

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

- J2SE 6.0 (Java 1.6) และสูงกว่า
- แพ็คเกจ Java เป็นแพลตฟอร์มข้ามแพลตฟอร์มและทำงานบนระบบปฏิบัติการทั้งหมดที่มีการใช้งาน JVM

<br />
สำหรับรายละเอียดเพิ่มเติม โปรดดูที่ [เอกสารประกอบผลิตภัณฑ์](https://docs.aspose.com/slides/java/system-requirements/)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}