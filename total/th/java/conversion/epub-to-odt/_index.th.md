---
title: Java API เพื่อส่งออก EPUB ไปยัง ODT
description: แปลง EPUB เป็น ODT โดยใช้ Java API . ในตัว
url_ignore: /th/java/conversion/epub-to-odt/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: ODT
otherformats: DOT DOTM PS XAMLFLOW MHTML RTF DOTX PCL FLATOPC MARKDOWN WORDML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง EPUB เป็น ODT ผ่าน Java" h2="บน Premise Java API เพื่อแสดงผล EPUB เป็น ODT โดยไม่ต้องใช้แอปพลิเคชันบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง EPUB เป็น ODT โดยใช้สองขั้นตอนง่ายๆ ก่อนอื่น คุณต้องแสดงไฟล์ EPUB เป็น DOC โดยใช้ [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะสามารถแปลง DOC เป็น ODT ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง EPUB เป็น ODT" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง EPUB เป็น DOC โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ ODT โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า ODT เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-odt.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะแปลง EPUB เป็น ODT แม้ว่าเอกสารของคุณจะมีการป้องกันด้วยรหัสผ่าน คุณยังสามารถเปิดได้โดยใช้ PDF Manipulation API [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) ในการเปิดไฟล์ที่เข้ารหัส คุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิด EPUB โดยใช้รหัสผ่านของเจ้าของ  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดเอกสาร EPUB ที่ป้องกันด้วยรหัสผ่านผ่าน Java" %}}
ในขณะที่บันทึกเอกสารอินพุตของคุณเป็นรูปแบบไฟล์ ODT คุณยังสามารถบันทึกเอกสารของคุณไปยังฐานข้อมูลแทนระบบไฟล์ คุณอาจต้องใช้การจัดเก็บและเรียกวัตถุเอกสารเข้าและออกจากฐานข้อมูล สิ่งนี้จำเป็นหากคุณใช้ระบบจัดการเนื้อหาประเภทใดก็ตาม ในการบันทึก ODT ลงในฐานข้อมูล จำเป็นต้องทำให้เอกสารเป็นอนุกรมเพื่อรับอาร์เรย์ไบต์ ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for Java](https://products.aspose.com/words/Java/) หลังจากได้รับอาร์เรย์ไบต์ของคุณแล้ว คุณสามารถจัดเก็บไว้ในฐานข้อมูลโดยใช้คำสั่ง SQL 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.ODT);
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
การแปลง **EPUB เป็น ODT (OpenDocument Text)** เป็นสิ่งจำเป็นสำหรับสร้างเอกสารข้อความมาตรฐานเปิดจาก eBook และสิ่งพิมพ์ดิจิทัล ไฟล์ ODT ช่วยให้มีความเข้ากันได้กับแพลตฟอร์มทุกแห่ง สามารถแก้ไขเนื้อหาได้ และเป็นไปตามมาตรฐานเปิด โดยการแปลง EPUB เป็น ODT ผู้สอน นักวิจัย สำนักพิมพ์ และองค์กรสามารถปรับปรุงการเขียนทางวิชาการ การกระจายเนื้อหา และการทำงานที่มีประสิทธิภาพในการเก็บถาวรได้อย่างมีประสิทธิภาพ

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}
- **การเขียนทางวิชาการ** – แปลง eBook เป็นเอกสารข้อความที่สามารถแก้ไขได้สำหรับการวิจัยและการมอบหมายงาน
- **การเผยแพร่แบบโอเพนซอร์ส** – แบ่งปันสิ่งพิมพ์ดิจิทัลในรูปแบบเปิดที่รองรับทั่วไป
- **การเก็บถาวรห้องสมุด** – รักษาเนื้อหาข้อความในรูปแบบมาตรฐานที่สามารถเข้าถึงได้
- **การกระจายเนื้อหาการศึกษา** – ส่งเรียนการสอนและวัสดุการเรียนการสอนในไฟล์ ODT ที่สามารถแก้ไขได้
- **เอกสารธุรกิจ** – รวมเนื้อหา eBook เข้ากับเอกสารที่เป็นมืออาชีพและเอกสารดำเนินงาน

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}
- **กระแสงาน EPUB เป็น ODT** – อัตโนมัติการแปลง eBook เป็นเอกสารข้อความ ODT
- **การแปลงเอกสารข้อความอัตโนมัติ** – ปรับปรุงกระบวนการการพิมพ์สำหรับไฟล์หลายๆ รายการ
- **การเผยแพร่ข้อมูลเชิงมาตรฐานเป็นข้อความ** – สกัดข้อมูล eBook โครงสร้างเข้าเอกสาร ODT สำหรับรายงานและการวิจัย
- **การอัตโนมัติเอกสาร ODT ในระดับองค์กร** – มาตรฐานการแปลงข้อความและการกระจายขนาดใหญ่และการกระจาย
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}