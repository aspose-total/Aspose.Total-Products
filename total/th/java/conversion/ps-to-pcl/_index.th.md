---
title: Java API เพื่อส่งออก PS ไปยัง PCL
description: แปลง PS เป็น PCL โดยใช้ Java API . ในตัว
url_ignore: /th/java/conversion/ps-to-pcl/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PCL
otherformats: OTT MARKDOWN RTF DOTM DOT FLATOPC MHTML PCL ODT XAMLFLOW WORDML DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง PS เป็น PCL ผ่าน Java" h2="บน Premise Java API เพื่อแสดงผล PS เป็น PCL โดยไม่ต้องใช้แอปพลิเคชันบุคคลที่สาม" >}}
{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถแปลง PS เป็น PCL โดยใช้สองขั้นตอนง่ายๆ ก่อนอื่น คุณต้องแสดงไฟล์ PS เป็น DOC โดยใช้ [Aspose.PDF สำหรับ Java](https://products.aspose.com/pdf/java/) หลังจากนั้น ด้วยการใช้ API การประมวลผลเอกสารอันทรงพลัง [Aspose.Words for Java](https://products.aspose.com/words/java/) คุณจะสามารถแปลง DOC เป็น PCL ได้ API ทั้งสองอยู่ภายใต้แพ็คเกจ [Aspose.Total for Java](https://products.aspose.com/total/java/)
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API เพื่อแปลง PS เป็น PCL" %}}
1. เปิดไฟล์ PS โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง PS เป็น DOC โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) กระบวนการ
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ PCL โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า PCL เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total สำหรับ Java ได้โดยตรงจากโปรเจ็กต์ที่ใช้ [Maven](https://releases.aspose.com/total/java/) และรวม [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) และ [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) ใน pom.xml ของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/java)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="ข้อกำหนดการแปลง" %}}
ขณะแปลง PS เป็น PCL แม้ว่าเอกสารของคุณจะมีการป้องกันด้วยรหัสผ่าน คุณยังสามารถเปิดได้โดยใช้ PDF Manipulation API [Aspose.PDF สำหรับ Java](https://docs.aspose.com/pdf/java/installation/) ในการเปิดไฟล์ที่เข้ารหัส คุณต้องสร้างวัตถุ [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) และเปิด PS โดยใช้รหัสผ่านของเจ้าของ  
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
ในขณะที่บันทึกเอกสารอินพุตของคุณเป็นรูปแบบไฟล์ PCL คุณยังสามารถบันทึกเอกสารของคุณไปยังฐานข้อมูลแทนระบบไฟล์ คุณอาจต้องใช้การจัดเก็บและเรียกวัตถุเอกสารเข้าและออกจากฐานข้อมูล สิ่งนี้จำเป็นหากคุณใช้ระบบจัดการเนื้อหาประเภทใดก็ตาม ในการบันทึก PCL ลงในฐานข้อมูล จำเป็นต้องทำให้เอกสารเป็นอนุกรมเพื่อรับอาร์เรย์ไบต์ ซึ่งสามารถทำได้โดยใช้ API [Aspose.Words for Java](https://products.aspose.com/words/Java/) หลังจากได้รับอาร์เรย์ไบต์ของคุณแล้ว คุณสามารถจัดเก็บไว้ในฐานข้อมูลโดยใช้คำสั่ง SQL 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PCL);
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

การแปลง PS (PostScript) เป็น PCL (Printer Command Language) ช่วยเพิ่มประสิทธิภาพของการพิมพ์โดยการ render ได้เร็วขึ้น ลดขนาด spool และมีความเข้ากันได้กับเครื่องพิมพ์ในสำนักงานและองค์กรอย่างกว้างขวาง การแปลงนี้เป็นสิ่งจำเป็นสำหรับองค์กรที่มาตรฐานในการใช้ PCL เพื่อผลลัพธ์เอกสารที่สม่ำเสมอและประสิทธิภาพที่ไม่ขึ้นอยู่กับอุปกรณ์

{{% blocks/products/pf/agp/feature-section-col title="Use Cases ที่สำคัญ" %}}

* การแปลงรายงาน PS ที่มีการออกแบบหนักเป็น PCL ที่มีน้ำหนักเบาสำหรับการพิมพ์ที่เร็ว
* มาตรฐานรูปแบบเอกสารสำหรับเครื่องพิมพ์ multifunction ในสภาพแวดล้อมองค์กร
* เตรียมสื่อการตลาด ใบแจ้งหนี้ และคู่มือเทคนิคสำหรับเครื่องพิมพ์ที่ใช้ PCL
* การเปิดให้บริการพิมพ์ตามความต้องการเพื่อสนับสนุนการทำงานของ PCL-native

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="สถานการณ์การใช้งานอัตโนมัติ" %}}

* การรวมเข้ากับระบบการจัดการการพิมพ์สำหรับการแปลง PS เป็น PCL โดยอัตโนมัติ
* การประมวลผลเป็นชุดในเซิร์ฟเวอร์การพิมพ์ในองค์กรสำหรับการจัดรูปแบบผลลัพธ์อย่างสม่ำเสมอ
* การ render เอกสารไดนามิกในระบบ ERP หรือ CRM ก่อนส่งพิมพ์
* การสร้างเอกสารพร้อมพิมพ์โดยอัตโนมัติสำหรับสภาพแวดล้อมการพิมพ์ขนาดใหญ่

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}