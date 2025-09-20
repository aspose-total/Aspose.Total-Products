---
title: Java API เพื่อส่งออก EPUB ไปยัง MHTML
description: แปลง EPUB เป็น MHTML โดยใช้ Java API . ในตัว
url_ignore: /th/java/conversion/epub-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: MHTML
otherformats: PS WORDML MARKDOWN PCL ODT RTF FLATOPC OTT XAMLFLOW DOTX MHTML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง EPUB เป็น MHTML ผ่าน Java" h2="บน Premise Java API เพื่อแสดงผล EPUB เป็น MHTML โดยไม่ต้องใช้แอปพลิเคชันบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง EPUB เป็น MHTML โดยใช้สองขั้นตอนง่ายๆ ก่อนอื่น คุณต้องแสดงไฟล์ EPUB เป็น DOC โดยใช้ [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะสามารถแปลง DOC เป็น MHTML ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง EPUB เป็น MHTML" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง EPUB เป็น DOC โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ MHTML โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า MHTML เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะแปลง EPUB เป็น MHTML แม้ว่าเอกสารของคุณจะมีการป้องกันด้วยรหัสผ่าน คุณยังสามารถเปิดได้โดยใช้ PDF Manipulation API [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) ในการเปิดไฟล์ที่เข้ารหัส คุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิด EPUB โดยใช้รหัสผ่านของเจ้าของ  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดเอกสาร EPUB ที่ป้องกันด้วยรหัสผ่านผ่าน Java" %}}
ในขณะที่บันทึกเอกสารอินพุตของคุณเป็นรูปแบบไฟล์ MHTML คุณยังสามารถบันทึกเอกสารของคุณไปยังฐานข้อมูลแทนระบบไฟล์ คุณอาจต้องใช้การจัดเก็บและเรียกวัตถุเอกสารเข้าและออกจากฐานข้อมูล สิ่งนี้จำเป็นหากคุณใช้ระบบจัดการเนื้อหาประเภทใดก็ตาม ในการบันทึก MHTML ลงในฐานข้อมูล จำเป็นต้องทำให้เอกสารเป็นอนุกรมเพื่อรับอาร์เรย์ไบต์ ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for Java](https://products.aspose.com/words/Java/) หลังจากได้รับอาร์เรย์ไบต์ของคุณแล้ว คุณสามารถจัดเก็บไว้ในฐานข้อมูลโดยใช้คำสั่ง SQL 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MHTML);
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
การแปลง **EPUB เป็น MHTML (Web Archive)** เป็นสิ่งสำคัญสำหรับการสร้าง **เอกสารเว็บแบบไฟล์เดียว** จากการพิมพ์ดิจิทัล ไฟล์ MHTML รวมทรัพยากรทั้งหมด—HTML, รูปภาพ, และสไตล์—เข้าไว้ในสิ่งสำคัญเดียว ทำให้สามารถพกพาได้, อ่านแบบออฟไลน์, และเข้ากันได้กับเบราว์เซอร์ โดยการแปลง EPUB เป็น MHTML, สำนักพิมพ์, ผู้สอน, และองค์กรสามารถส่งสิ่งพิมพ์อิเล็กทรอนิกส์เป็นเอกสารเว็บแบบเองที่ถูกปรับแต่งให้เหมาะสำหรับการใช้ทั้งออนไลน์และออฟไลน์

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}
- **การอ่าน eBook แบบออฟไลน์** – ให้หนังสือดิจิทัลทั้งหมดที่สามารถเข้าถึงได้โดยไม่ต้องอินเทอร์เน็ต
- **การเก็บถาวรเว็บ** – รักษาเนื้อหา eBook เป็นสิ่งสำคัญเดียวที่เข้ากันได้กับเบราวเซอร์
- **การเผยแพร่ดิจิทัลสำหรับเบราวเซอร์** – แบ่งปันเนื้อหา EPUB ในรูปแบบเว็บที่พร้อมใช้งาน
- **การแพ็คเนื้อหาการศึกษา** – แจกจ่ายบทเรียน, วัสดุการเรียนรู้, และ eBook ในไฟล์พกพา
- **กระบวนการเอกสารขององค์กร** – ปรับปรุงการพิมพ์ภายในเป็นเอกสารพร้อมใช้งานในเบราวเซอร์
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}
- **กระแสงาน EPUB เป็น MHTML** – อัตโนมัติการแปลงการพิมพ์ดิจิทัลเป็นสิ่งสำคัญเดียวเว็บ
- **กระบวนการงาน eBook เป็นเว็บอัตโนมัติ** – ทำให้การเผยแพร่ EPUB เข้าสู่รูปแบบที่รองรับโดยเบราวเซอร์ง่ายขึ้น
- **การเผยแพร่เป็นกลุ่มสำหรับการเข้าถึงแบบออฟไลน์** – แปลงไบรารีหนังสือทั้งหมดเป็น MHTML เพื่อความพกพา
- **การเผยแพร่ที่เข้ากันได้กับเบราวเซอร์跨แพลตฟอร์ม** – รับรองการอ่านอย่างไม่มีข้อขัดข้องในเบราวเซอร์ทุกตัว
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}