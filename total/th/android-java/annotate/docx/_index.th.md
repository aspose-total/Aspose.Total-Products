---
title: ลบคำอธิบายประกอบ DOCX ออนไลน์หรือจัดการคำอธิบายประกอบโดยใช้แอพมือถือ Android
description: ลบความคิดเห็นออกจากไฟล์ DOCX ผ่านแอปออนไลน์ฟรีรหัส Android API เพื่อจัดการความคิดเห็นของไฟล์ DOCX

family: total
platformtag: Android
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="ล้างความคิดเห็นจากเอกสาร DOCX ออนไลน์หรือจัดการผ่านแอพ Android" h2="พัฒนาแอปพลิเคชันยูทิลิตี้คำอธิบายประกอบเอกสาร DOCX ที่ใช้ Android ที่ทรงพลังรหัสที่แสดงสำหรับการจัดการความคิดเห็นของไฟล์ DOCX" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ลบคำอธิบายประกอบ DOCX ออนไลน์" %}}

1. นำเข้าไฟล์ DOCX เพื่อลบความคิดเห็นโดยการอัปโหลด
1. ทำได้โดยการคลิกภายในพื้นที่วางผ่านการลากและวางของแอปคำอธิบายประกอบ
1. ขึ้นอยู่กับขนาดของไฟล์ DOCX และความเร็วอินเตอร์เน็ต ให้รอสักครู่
1. คลิกปุ่ม 'ลบ' เพื่อล้างความคิดเห็น
1. ดาวน์โหลดไฟล์ได้ทันที

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ลบความคิดเห็นเอกสาร DOCX ผ่านแอพ Android" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Android
1. โหลดเอกสารผ่านวัตถุคลาสเอกสาร
1. รับความคิดเห็นทั้งหมดจากโหนดทั้งหมดโดยใช้ [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) และ NodeType.COMMENT
1. เรียกใช้วิธี [clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear) เพื่อลบความคิดเห็นทั้งหมด
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส : ลบความคิดเห็นออกจากไฟล์ DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ลบและเพิ่มการตอบกลับความคิดเห็น DOCX" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Android
1. โหลดเอกสารผ่านวัตถุคลาสเอกสาร
1. รับความคิดเห็นโดยใช้ getChild
1. ใช้ [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) เพื่อลบการตอบกลับที่ระบุสำหรับความคิดเห็นนี้
1. ใช้ [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) เพื่อเพิ่มการตอบกลับความคิดเห็นนี้
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="เพิ่มความคิดเห็นผ่านแอพ Android" %}}

1. เพิ่มการอ้างอิงไลบรารีให้กับโครงการ Android
1. สร้างวัตถุคลาสเอกสาร
1. ใช้ [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) เพื่อสร้างความคิดเห็น
1. ใช้ getParagraphs().add และ getFirstParagraph().getRuns().add
1. เรียกวิธีการบันทึกเพื่อบันทึกไฟล์ with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="รหัส : ลบและเพิ่มการตอบกลับความคิดเห็นจากไฟล์ DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="รหัส: การเพิ่มความคิดเห็น" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>พัฒนาแอพ Android คำอธิบายประกอบเอกสาร DOCX</h2>

ต้องการพัฒนาแอปหรือยูทิลิตี้คำอธิบายประกอบ DOCX บนมือถือเพื่อให้คำติชม ให้คำแนะนำ หรือทำงานร่วมกับผู้อื่นในเอกสารหรือไม่ด้วย [Aspose.Words for Android via Java](https://products.aspose.com/words/th/android-java/) ซึ่งเป็น API ลูกของ [Aspose.Total for Android via Java](https://products.aspose.com/total/th/android-java/) นักพัฒนา Android ทุกคนสามารถรวมโค้ด API ข้างต้นภายในแอปพลิเคชันคำอธิบายประกอบเอกสารได้ไลบรารี Android อันทรงพลังช่วยให้สามารถเขียนโปรแกรมโซลูชันคำอธิบายประกอบเอกสารได้นอกจากนี้ยังสามารถรองรับรูปแบบยอดนิยมมากมายรวมถึงรูปแบบ DOCX<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ไลบรารี Android เพื่อใส่คำอธิบายประกอบไฟล์ DOCX" %}}

- เราโฮสต์แพ็คเกจ Java ของเราใน [ที่เก็บ Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/) 
- Aspose.Words for Java เป็นไฟล์ JAR ทั่วไปที่มีรหัสไบต์
- ทำตาม [คำแนะนำทีละขั้นตอน](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) เกี่ยวกับวิธีการติดตั้ง Aspose.Words for Android via Java

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

- รองรับ Java SE 7 และ Java เวอร์ชันล่าสุด
- แยกแพ็คเกจสำหรับ Java SE 6 ในกรณีที่จำเป็นต้องใช้ JRE ที่ล้าสมัย
- แพ็คเกจ Java เป็นแพลตฟอร์มข้ามแพลตฟอร์มและทำงานบนระบบปฏิบัติการทั้งหมดที่มีการใช้งาน JVM
- ระบบปฏิบัติการ ได้แก่ Microsoft Windows, Linux, macOS, Android และ iOS

<br />
สำหรับรายละเอียดเพิ่มเติมเกี่ยวกับการขึ้นต่อกันของแพ็คเกจเสริม เช่น JogAmp JOGL, เอ็นจิ้นแบบอักษร Harfbuzz, Java Advanced Imaging JAI โปรดดูที่ [เอกสารประกอบผลิตภัณฑ์](https://docs.aspose.com/words/java/system-requirements/)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}