---
title: Java API เพื่อส่งออก EPUB ไปยัง MARKDOWN
description: แปลง EPUB เป็น MARKDOWN โดยใช้ Java API . ในตัว
url_ignore: /th/java/conversion/epub-to-markdown/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: MARKDOWN
otherformats: MARKDOWN DOT PCL ODT FLATOPC WORDML XAMLFLOW DOTX RTF DOTM PS OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง EPUB เป็น MARKDOWN ผ่าน Java" h2="บน Premise Java API เพื่อแสดงผล EPUB เป็น MARKDOWN โดยไม่ต้องใช้แอปพลิเคชันบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง EPUB เป็น MARKDOWN โดยใช้สองขั้นตอนง่ายๆ ก่อนอื่น คุณต้องแสดงไฟล์ EPUB เป็น DOC โดยใช้ [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะสามารถแปลง DOC เป็น MARKDOWN ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง EPUB เป็น MARKDOWN" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง EPUB เป็น DOC โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ MARKDOWN โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า MARKDOWN เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-markdown.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะแปลง EPUB เป็น MARKDOWN แม้ว่าเอกสารของคุณจะมีการป้องกันด้วยรหัสผ่าน คุณยังสามารถเปิดได้โดยใช้ PDF Manipulation API [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) ในการเปิดไฟล์ที่เข้ารหัส คุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิด EPUB โดยใช้รหัสผ่านของเจ้าของ  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดเอกสาร EPUB ที่ป้องกันด้วยรหัสผ่านผ่าน Java" %}}
ในขณะที่บันทึกเอกสารอินพุตของคุณเป็นรูปแบบไฟล์ MARKDOWN คุณยังสามารถบันทึกเอกสารของคุณไปยังฐานข้อมูลแทนระบบไฟล์ คุณอาจต้องใช้การจัดเก็บและเรียกวัตถุเอกสารเข้าและออกจากฐานข้อมูล สิ่งนี้จำเป็นหากคุณใช้ระบบจัดการเนื้อหาประเภทใดก็ตาม ในการบันทึก MARKDOWN ลงในฐานข้อมูล จำเป็นต้องทำให้เอกสารเป็นอนุกรมเพื่อรับอาร์เรย์ไบต์ ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for Java](https://products.aspose.com/words/Java/) หลังจากได้รับอาร์เรย์ไบต์ของคุณแล้ว คุณสามารถจัดเก็บไว้ในฐานข้อมูลโดยใช้คำสั่ง SQL 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MARKDOWN);
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
การแปลง **EPUB เป็น Markdown** มีความคุ้มค่าอย่างมากสำหรับการสร้าง **ไฟล์เนื้อหาที่เบา และเป็นมิตรกับนักพัฒนา** จากการพิมพ์เผยแพร่ดิจิทัล  Markdown ช่วยให้ง่ายต่อการใช้งาน สามารถใช้งานได้บนหลายแพลตฟอร์ม และผสานอย่างไม่มีรอยต่อกับเครื่องมือสร้างเว็บไซต์แบบสถิต โดยการแปลง EPUB เป็น Markdown สำนักพิมพ์ นักพัฒนาซอฟต์แวร์ และชุมชนโอเพนซอร์สสามารถนำเนื้อหาหนังสืออิเล็กทรอนิกส์มาใช้ใหม่สำหรับงานเขียนเอกสาร บล็อก และการเผยแพร่ร่วมกัน

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}
- **การเผยแพร่เว็บไซต์แบบสถิต** – ให้กำลังให้ชีวิตเว็บไซต์ที่ทันสมัยด้วยเนื้อหา eBook ที่ใช้ Markdown
- **การจัดการเอกสารบน GitHub** – จัดการและควบคุมเวอร์ชันของเนื้อหาโดยตรงในที่เก็บ Git
- **การแบ่งปัน eBook แบบโอเพนซอร์ส** – แจกจ่ายหนังสือในรูปแบบ Markdown ที่สามารถอ่านได้ทั่วไป
- **การเขียนบล็อกทางเทคนิค** – แปลงบทของ eBook เป็นเนื้อหาบล็อกที่เป็นมิตรกับนักพัฒนา
- **กระบวนการเผยแพร่ที่เป็นมิตรกับนักพัฒนา** – เปิดให้ใช้งานการจัดการเนื้อหาที่เบาและพกพาได้
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การใช้งานอัตโนมัติ" %}}
- **กระบวนการท่องไปยัง Markdown** – ทำให้การแปลง eBook เป็น Markdown เป็นอัตโนมัติสำหรับการเผยแพร่ที่มีขนาดใหญ่
- **การเผยแพร่อัตโนมัติไปยังระบบที่ใช้ Git** – ประสานเนื้อหา eBook กับที่เก็บข้อมูลเช่น GitHub หรือ GitLab
- **การสร้างเว็บไซต์แบบสถิต** – นำเนื้อหา Markdown เข้าสู่ Jekyll, Hugo, หรือ Next.js สำหรับการเผยแพร่บนเว็บ
- **การอัตโนมัติเอกสารขององค์กร** – มาตรฐานกระบวนการทำงานเอกสารด้วยผลลัพธ์ Markdown
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}