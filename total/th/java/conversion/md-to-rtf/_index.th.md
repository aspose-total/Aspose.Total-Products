---
title: Java API เพื่อส่งออก MD ไปยัง RTF
description: แปลง MD เป็น RTF โดยใช้ Java API . ในตัว
url_ignore: /th/java/conversion/md-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: RTF
otherformats: DOTM DOT PCL ODT PS MARKDOWN RTF XAMLFLOW WORDML OTT DOTX FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง MD เป็น RTF ผ่าน Java" h2="บน Premise Java API เพื่อแสดงผล MD เป็น RTF โดยไม่ต้องใช้แอปพลิเคชันบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง MD เป็น RTF โดยใช้สองขั้นตอนง่ายๆ ก่อนอื่น คุณต้องแสดงไฟล์ MD เป็น DOC โดยใช้ [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะสามารถแปลง DOC เป็น RTF ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง MD เป็น RTF" %}}
1. เปิดไฟล์ MD โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง MD เป็น DOC โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ RTF โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า RTF เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะแปลง MD เป็น RTF แม้ว่าเอกสารของคุณจะมีการป้องกันด้วยรหัสผ่าน คุณยังสามารถเปิดได้โดยใช้ PDF Manipulation API [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) ในการเปิดไฟล์ที่เข้ารหัส คุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิด MD โดยใช้รหัสผ่านของเจ้าของ  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดเอกสาร MD ที่ป้องกันด้วยรหัสผ่านผ่าน Java" %}}
ในขณะที่บันทึกเอกสารอินพุตของคุณเป็นรูปแบบไฟล์ RTF คุณยังสามารถบันทึกเอกสารของคุณไปยังฐานข้อมูลแทนระบบไฟล์ คุณอาจต้องใช้การจัดเก็บและเรียกวัตถุเอกสารเข้าและออกจากฐานข้อมูล สิ่งนี้จำเป็นหากคุณใช้ระบบจัดการเนื้อหาประเภทใดก็ตาม ในการบันทึก RTF ลงในฐานข้อมูล จำเป็นต้องทำให้เอกสารเป็นอนุกรมเพื่อรับอาร์เรย์ไบต์ ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for Java](https://products.aspose.com/words/Java/) หลังจากได้รับอาร์เรย์ไบต์ของคุณแล้ว คุณสามารถจัดเก็บไว้ในฐานข้อมูลโดยใช้คำสั่ง SQL 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.RTF);
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



การแปลง MD (Markdown) เป็น RTF (Rich Text Format) ช่วยให้ไฟล์สามารถใช้งานได้บนหลายแพลตฟอร์มและมีความสามารถในการเข้าถึงข้อมูลได้ง่ายขึ้น ไฟล์ RTF รักษาสไตล์ได้ทั่วไปบนระบบปฏิบัติการเกือบทุกแพลตฟอร์ม ทำให้เหมาะสำหรับการกระจายข้อมูลอย่างเบา การเก็บถาวร และการเข้าถึงข้อมูลแบบออฟไลน์



{{% blocks/products/pf/agp/feature-section-col title="การใช้งานหลัก" %}}



* การแปลงเอกสาร Markdown เป็นคู่มือ RTF ที่สามารถพกพาได้

* สร้างแผ่นงานการฝึกอบรมที่เข้ากันได้กับทุกแพลตฟอร์มจากคู่มือ MD

* ไฟล์ช่วยเหลือที่ใช้รูปแบบ RTF ที่มาจาก Markdown สำหรับระบบเก่า

* เอกสารข้อความที่เข้าถึงได้แบบออฟไลน์สำหรับทีมที่มีการเข้าถึงซอฟต์แวร์จำกัด



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}



* การสร้างเอกสาร MD-to-RTF ตามกำหนดเวลาสำหรับคลังข้อมูลดิจิทัล

* การสร้างกระบวนการทำงาน ETL ที่ส่งออกเนื้อหาจากคลังข้อมูลเป็นไลบรารี RTF

* การสร้างไฟล์ RTF โดยอัตโนมัติสำหรับชุดช่วยเหลือลูกค้าแบบออฟไลน์

* การแปลงบทช่วยเหลือ Markdown เป็นไฟล์ RTF ที่เข้ากันได้กับหลายแพลตฟอร์มโดยเป็นกลุ่ม



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}