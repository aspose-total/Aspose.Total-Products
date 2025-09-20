---
title: Java API เพื่อส่งออก EPUB ไปยัง XAMLFLOW
description: แปลง EPUB เป็น XAMLFLOW โดยใช้ Java API . ในตัว
url_ignore: /th/java/conversion/epub-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: XAML_FLOW
otherformats: MARKDOWN DOTM PCL DOT WORDML DOTX FLATOPC XAMLFLOW ODT PS MHTML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง EPUB เป็น XAMLFLOW ผ่าน Java" h2="บน Premise Java API เพื่อแสดงผล EPUB เป็น XAMLFLOW โดยไม่ต้องใช้แอปพลิเคชันบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง EPUB เป็น XAMLFLOW โดยใช้สองขั้นตอนง่ายๆ ก่อนอื่น คุณต้องแสดงไฟล์ EPUB เป็น DOC โดยใช้ [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะสามารถแปลง DOC เป็น XAMLFLOW ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง EPUB เป็น XAMLFLOW" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง EPUB เป็น DOC โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ XAMLFLOW โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า XAMLFLOW เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-xaml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะแปลง EPUB เป็น XAMLFLOW แม้ว่าเอกสารของคุณจะมีการป้องกันด้วยรหัสผ่าน คุณยังสามารถเปิดได้โดยใช้ PDF Manipulation API [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) ในการเปิดไฟล์ที่เข้ารหัส คุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิด EPUB โดยใช้รหัสผ่านของเจ้าของ  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.epub", "password");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดเอกสาร EPUB ที่ป้องกันด้วยรหัสผ่านผ่าน Java" %}}
ในขณะที่บันทึกเอกสารอินพุตของคุณเป็นรูปแบบไฟล์ XAMLFLOW คุณยังสามารถบันทึกเอกสารของคุณไปยังฐานข้อมูลแทนระบบไฟล์ คุณอาจต้องใช้การจัดเก็บและเรียกวัตถุเอกสารเข้าและออกจากฐานข้อมูล สิ่งนี้จำเป็นหากคุณใช้ระบบจัดการเนื้อหาประเภทใดก็ตาม ในการบันทึก XAMLFLOW ลงในฐานข้อมูล จำเป็นต้องทำให้เอกสารเป็นอนุกรมเพื่อรับอาร์เรย์ไบต์ ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for Java](https://products.aspose.com/words/Java/) หลังจากได้รับอาร์เรย์ไบต์ของคุณแล้ว คุณสามารถจัดเก็บไว้ในฐานข้อมูลโดยใช้คำสั่ง SQL 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.XAML_FLOW);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
การแปลง **EPUB เป็น XAMLFLOW** เป็นสิ่งจำเป็นสำหรับการสร้าง **เค้าโครงเอกสารที่ขึ้นอยู่กับการไหล** สำหรับแอปพลิเคชันที่ทันสมัย XAMLFLOW ทำให้เนื้อหาเป็นไดนามิก แอ็คทีฟ และปรับการแสดงเนื้อหาได้ ทำให้เหมาะสำหรับการเผยแพร่ดิจิทัล การแสดงผลการวิจัย และเอกสารที่ขับเคลื่อนโดยแอปพลิเคชัน โดยการแปลง EPUB เป็น XAMLFLOW สำนักพิมพ์และนักพัฒนาสามารถสร้างเค้าโครงที่ตอบสนองได้ซึ่งเพิ่มความอ่านง่าย ความสนใจ และประสิทธิภาพข้ามแพลตฟอร์ม

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}
- **กระบวนการทำงานในการเผยแพร่ดิจิทัล** – ปรับปรุงเค้าโครง eBook ที่เป็นไดนามิกและแอ็คทีฟ
- **eBook ที่เป็นไดนามิก** – เพิ่มความสนใจของผู้ใช้ด้วยเนื้อหาที่เป็นไดนามิกและขึ้นอยู่กับการไหล
- **เนื้อหาที่ขับเคลื่อนโดยแอปพลิเคชัน** – ผสานการเผยแพร่เข้ากับอินเตอร์เฟซที่ขึ้นอยู่กับแอปพลิเคชันอย่างไม่มีรอยต่อ
- **การแสดงผลเอกสารการวิจัย** – นำเสนอชุดข้อมูลที่ซับซ้อนและการเผยแพร่ในลำดับที่มีโครงสร้างและอ่านง่าย
- **เค้าโครงที่เป็นไดนามิก** – เปิดให้ใช้งานการออกแบบที่ตอบสนองได้บนอุปกรณ์และแพลตฟอร์ม
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การใช้งานอัตโนมัติ" %}}
- **กระบวนการทำงาน EPUB เป็น XAMLFLOW** – อัตโนมัติการแปลง eBook เป็นเค้าโครงที่ขึ้นอยู่กับการไหล
- **การสร้างเอกสารที่เป็นไดนามิกโดยอัตโนมัติ** – สร้างเอกสารที่เป็นไดนามิกจากเนื้อหาการเผยแพร่
- **การแปลงเนื้อหาเป็นก้อนใหญ่** – แปลงไบรารีขนาดใหญ่ของ EPUB เป็น XAMLFLOW อย่างมีประสิทธิภาพ
- **แอปพลิเคชันการเผยแพร่ระดับองค์กร** – ผสานการสร้าง XAMLFLOW เข้ากับแพลตฟอร์มการเผยแพร่ดิจิทัลที่มีขนาดใหญ่
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}