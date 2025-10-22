---
title: Java API เพื่อส่งออก PS ไปยัง XAMLFLOW
description: แปลง PS เป็น XAMLFLOW โดยใช้ Java API . ในตัว
url_ignore: /th/java/conversion/ps-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XAML_FLOW
otherformats: WORDML DOTM MHTML DOT FLATOPC ODT XAMLFLOW RTF PCL OTT MARKDOWN DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง PS เป็น XAMLFLOW ผ่าน Java" h2="บน Premise Java API เพื่อแสดงผล PS เป็น XAMLFLOW โดยไม่ต้องใช้แอปพลิเคชันบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง PS เป็น XAMLFLOW โดยใช้สองขั้นตอนง่ายๆ ก่อนอื่น คุณต้องแสดงไฟล์ PS เป็น DOC โดยใช้ [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะสามารถแปลง DOC เป็น XAMLFLOW ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง PS เป็น XAMLFLOW" %}}
1. เปิดไฟล์ PS โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง PS เป็น DOC โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ XAMLFLOW โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า XAMLFLOW เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS file with an instance of Document class
Document document = new Document("template.ps");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.XAML_FLOW
outputDocument.save("output.xaml_flow", SaveFormat.XAML_FLOW);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะแปลง PS เป็น XAMLFLOW แม้ว่าเอกสารของคุณจะมีการป้องกันด้วยรหัสผ่าน คุณยังสามารถเปิดได้โดยใช้ PDF Manipulation API [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) ในการเปิดไฟล์ที่เข้ารหัส คุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิด PS โดยใช้รหัสผ่านของเจ้าของ  
{{% blocks/products/pf/feature-page-code %}}
```cs
// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="เปิดเอกสาร PS ที่ป้องกันด้วยรหัสผ่านผ่าน Java" %}}
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

การแปลงไฟล์ PS (PostScript) เป็น XAMLFLOW ช่วยให้การผสานเข้ากันได้อย่างราบรื่นระหว่างเลย์เอาท์ของ PostScript เข้ากับแอปพลิเคชันที่ขับเคลื่อนด้วยเวิร์กโฟลว์และท่อไฟล์อัตโนมัติโดยใช้เวิร์กโฟลว์ที่ใช้ XAML รูปแบบนี้เหมาะสำหรับการแสดงผลทางด้านภาพเคลื่อนไหวและตรรกะแอปพลิเคชันที่มีประสิทธิภาพ

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}

* การแปลงไดอะแกรม PS เพื่อใช้ในแอปพลิเคชันเชิงเวิร์กโฟลว์อัตโนมัติ
* ฝังกราฟิก PostScript เข้าไปในการแสดงกระบวนการที่ใช้ XAML
* การแปลงเลย์เอาท์ PS เพื่อใช้เป็นส่วนประกอบ UI ที่เคลื่อนไหวได้ในซอฟต์แวร์เชิงเวิร์กโฟลว์
* เตรียมภาพทางเทคนิคและดำเนินการสำหรับการอัตโนมัติที่ขับเคลื่อนด้วยแอปพลิเคชัน

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์อัตโนมัติ" %}}

* การแปลง PS เป็น XAMLFLOW โดยอัตโนมัติสำหรับการผสานระบบเวิร์กโฟลว์
* ประมวลผลแบบกลุ่มของทรัพยากร PS สำหรับท่อไฟล์แอปพลิเคชันเคลื่อนไหว
* การปรับปรุงกราฟิกด้วยการช่วยเหลือของ AI สำหรับการแสดงผลเวิร์กโฟลว์แบบแอปพลิเคชัน
* การแปลงตารางเวลาสำหรับการอัพเดตแอปพลิเคชันอย่างต่อเนื่องด้วยภาพ PS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}