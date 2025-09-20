---
title: Java API เพื่อส่งออก EPUB ไปยัง DOTM
description: แปลง EPUB เป็น DOTM โดยใช้ Java API . ในตัว
url_ignore: /th/java/conversion/epub-to-dotm/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: DOTM
otherformats: FLATOPC ODT XAMLFLOW DOTX DOTM RTF OTT MARKDOWN PCL MHTML WORDML PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง EPUB เป็น DOTM ผ่าน Java" h2="บน Premise Java API เพื่อแสดงผล EPUB เป็น DOTM โดยไม่ต้องใช้แอปพลิเคชันบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง EPUB เป็น DOTM โดยใช้สองขั้นตอนง่ายๆ ก่อนอื่น คุณต้องแสดงไฟล์ EPUB เป็น DOC โดยใช้ [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะสามารถแปลง DOC เป็น DOTM ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง EPUB เป็น DOTM" %}}
1. เปิดไฟล์ EPUB โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง EPUB เป็น DOC โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ DOTM โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า DOTM เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะแปลง EPUB เป็น DOTM แม้ว่าเอกสารของคุณจะมีการป้องกันด้วยรหัสผ่าน คุณยังสามารถเปิดได้โดยใช้ PDF Manipulation API [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) ในการเปิดไฟล์ที่เข้ารหัส คุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิด EPUB โดยใช้รหัสผ่านของเจ้าของ  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดเอกสาร EPUB ที่ป้องกันด้วยรหัสผ่านผ่าน Java" %}}
ในขณะที่บันทึกเอกสารอินพุตของคุณเป็นรูปแบบไฟล์ DOTM คุณยังสามารถบันทึกเอกสารของคุณไปยังฐานข้อมูลแทนระบบไฟล์ คุณอาจต้องใช้การจัดเก็บและเรียกวัตถุเอกสารเข้าและออกจากฐานข้อมูล สิ่งนี้จำเป็นหากคุณใช้ระบบจัดการเนื้อหาประเภทใดก็ตาม ในการบันทึก DOTM ลงในฐานข้อมูล จำเป็นต้องทำให้เอกสารเป็นอนุกรมเพื่อรับอาร์เรย์ไบต์ ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for Java](https://products.aspose.com/words/Java/) หลังจากได้รับอาร์เรย์ไบต์ของคุณแล้ว คุณสามารถจัดเก็บไว้ในฐานข้อมูลโดยใช้คำสั่ง SQL 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOTM);
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
การแปลง **EPUB เป็น DOTM** เป็นสิ่งสำคัญสำหรับการสร้าง **เทมเพลต Word ที่เปิดใช้งานมาโคร** จาก eBook และการพิมพ์ดิจิทัล DOTM ช่วยให้การอัตโนมัติขั้นสูงผ่านมาโครที่ฝังอยู่เป็นไปได้ ทำให้สำนักพิมพ์ นักวิจัย และองค์กรสามารถปรับปรุงการทำงาน ลดความพยายามในการทำด้วยมือ และมาตรฐานการสร้างเนื้อหา โดยการแปลง EPUB เป็น DOTM องค์กรสามารถรวมฟังก์ชันไดนามิกเข้ากับเทมเพลตที่ใช้ซ้ำ ทำให้มีประสิทธิภาพและคงสภาพในการเขียนเอกสารทางวิชาการ ธุรกิจ และการศึกษา

{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}
- **เทมเพลตการพิมพิการอัตโนมัติ** – เร่งความเร็วในการแปลง eBook เป็นเทมเพลตสำหรับแคตตาล็อกขนาดใหญ่
- **การอัตโนมัติในการวิจัยและการศึกษา** – สร้างกรอบมาตรฐานที่ใช้มาโครสำหรับการศึกษา
- **เทมเพลตสำหรับอินเทลลิเจนธุรกิจ** – อัตโนมัติรายงาน การรวมข้อมูล และเนื้อหาที่มีโคร
- **กรอบเนื้อหาการศึกษา** – สร้างเทมเพลตสำหรับหลักสูตรและเนื้อหาการเรียนการสอนที่เปิดใช้งานมาโคร
- **เทมเพลตที่ขับเคลื่อนด้วยขั้นตอนการทำงาน** – รวมมาโครเพื่ออัตโนมัติงานพิมพ์ที่ซ้ำซาก
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การอัตโนมัติ" %}}
- **กระแสการแปลง EPUB เป็น DOTM** – ปรับปรุงกระบวนการสร้างเทมเพลตจำนวนมากจากการพิมพ์ดิจิทัล
- **การกระจายเทมเพลตที่เปิดใช้งานมาโคร** – นำเทมเพลตที่เปิดใช้งานมาโครและแบ่งให้ทีมใช้งาน
- **การแปลงเมตาดาต้าเป็นเทมเพลต** – แปลงเมตาดาต้าทางวรรณกรรมและการพิมพ์เป็นไฟล์ DOTM ที่พร้อมใช้งาน
- **การอัตโนมัติการพิมพ์ขององค์กร** – สร้างกระบวนการที่เชื่อมต่อแหล่งที่มา EPUB กับเทมเพลต Word ที่เปิดใช้งานมาโคร
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}