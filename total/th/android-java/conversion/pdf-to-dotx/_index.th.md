---
title: Android API เพื่อแสดงผล PDF เป็น DOTX
description: แปลง PDF เป็น DOTX ผ่าน Android ผ่าน Java API

family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: DOTX
otherformats: XAMLFLOW WORDML ODT DOCM RTF MHTML OTT PCL DOT MARKDOWN PS FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="แสดงผล PDF เป็น DOTX บน Android ผ่าน Java" h2="แปลง PDF เป็น DOTX ในแอพมือถือโดยไม่ต้องติดตั้งซอฟต์แวร์ใดๆ" >}}

{{% blocks/products/pf/feature-page-summary %}}
คุณสามารถรวมคุณลักษณะการแปลง PDF เป็น DOTX ในแอปบนอุปกรณ์เคลื่อนที่ได้โดยใช้ API สองชุดของ [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/) ก่อนอื่น คุณต้องแปลงไฟล์ PDF เป็น DOC โดยใช้ [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) ประการที่สอง โดยใช้ Word Processing API [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) คุณสามารถแสดง DOC เป็น DOTX 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="แปลง PDF เป็น DOTX บน Android ผ่าน Java" %}}
1. เปิดไฟล์ PDF โดยใช้คลาส [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. แปลง PDF เป็น DOC โดยใช้ [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) กระบวนการ
3. โหลดไฟล์ DOC โดยใช้ [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) คลาสของ Aspose.Words
4. บันทึกเอกสารในรูปแบบ DOTX โดยใช้เมธอด [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) และตั้งค่า DOTX เป็น SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
คุณสามารถใช้ Aspose.Total for Android via Java ได้โดยตรงจาก [Maven](https://releases.aspose.com/total/java/) และ ติดตั้ง [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) และ [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) ในแอปพลิเคชันของคุณ

หรือคุณสามารถรับไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.comtotal/androidjava)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTX
outputDocument.save("output.dotx", SaveFormat.DOTX);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="รับข้อมูลไฟล์ PDF บน Android ผ่าน Java" %}}
ก่อนที่จะแปลง PDF เป็น DOTX คุณอาจต้องการข้อมูลเกี่ยวกับเอกสาร ซึ่งรวมถึงผู้แต่ง วันที่สร้าง คำหลัก วันที่แก้ไข หัวเรื่อง และชื่อเรื่อง ข้อมูลนี้มีประโยชน์สำหรับการตัดสินใจในกระบวนการแปลง ด้วยการใช้ [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) อันทรงพลัง คุณสามารถรับมันได้ทั้งหมด หากต้องการรับข้อมูลเฉพาะไฟล์เกี่ยวกับไฟล์ PDF ก่อนอื่นให้รับวัตถุ [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) โดยใช้ [getInfo](https://) วิธีอ้างอิง.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) เมื่อดึงวัตถุ DocumentInfo แล้ว คุณจะได้รับค่าของคุณสมบัติแต่ละรายการ
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF document
Document doc = new Document("template.pdf");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="แทรก Endnotes ในเอกสาร DOTX ใน Android ผ่าน Java" %}}
นอกเหนือจากการแปลงเอกสาร คุณยังสามารถเพิ่มคุณสมบัติอื่นๆ มากมายภายในแอปพลิเคชัน Android ของคุณโดยใช้ [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API หนึ่งในคุณสมบัตินั้นคือการแทรกอ้างอิงท้ายเรื่องและการกำหนดหมายเลขในเอกสาร DOTX หากคุณต้องการแทรกเชิงอรรถหรืออ้างอิงท้ายเรื่องในเอกสาร DOTX โปรดใช้วิธี DocumentBuilder.InsertFootnote วิธีนี้จะแทรกเชิงอรรถหรืออ้างอิงท้ายเรื่องลงในเอกสาร คลาส EndnoteOptions และ FootnoteOptions แสดงถึงตัวเลือกการกำหนดหมายเลขสำหรับเชิงอรรถและอ้างอิงท้ายเรื่อง
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.dotx", SaveFormat.DOTX);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}